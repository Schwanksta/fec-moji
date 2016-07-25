A Twitter bot that ingests the ProPublica campfin API and merges it with the Dango emoji API to produce a wonderful, Venmo-like Twitter feed of payment information.

Runs on the AWS Lambda infrastructure. It is kinda cool.

To get this working, you need an AWS account, a Twitter account, and a ProPublica Campaign Finance API key.

```bash
cp deploy.env.template deploy.env
cp deploy.env .env
```

And fill out both of those envs with your keys.
