# Hobby Documents

This is a static website which programmed by using hugo framework. Also Docsy theme is used.

Following websites might be useful somehow for gaining knowledges about hugo and Docsy theme.

- [Docsy user guide](https://docsy.dev/docs)
- [Docsy](https://github.com/google/docsy)
- [example.docsy.dev](https://example.docsy.dev)
- [Hugo theme module](https://gohugo.io/hugo-modules/use-modules/#use-a-module-for-a-theme)

## How to run website locally

Simply run following command for serving the website :

```bash
hugo server --bind 0.0.0.0
```

Then, open a web browser (for ex. google chrome), access localhost:1313.

## How to deploy the website onto GCP and google firebase

Currently, the gmail account hoaiphuong.nguyen.vn@gmail.com is used for GCP and google firebase related to this static website. This website is constructed under project named **hobby**.

https://console.firebase.google.com/

https://console.cloud.google.com/

Since github action is also configured, the deployment will be triggered automatically once a new commit comes to master branch. However, before commiting changes onto github repo, remember to run command ```hugo``` in order to generate static contents in directory **public**.

The url of the website is https://hobbydoc.nextai.world

For more information regarding to Hosting & Deployment hugo website onto firebase, please refer to [Host on Firebase](https://gohugo.io/hosting-and-deployment/hosting-on-firebase/)