## USING THIS TEMPLATE:

- Make sure to run npm install

- Environmental variables defined in env.yaml, so create a env.yaml that looks like this...

```yaml
development:
  PORT: 4000
  SECRET: "production"
 
production:
  PORT: 3000
  SECRET: "development"
```

- For production you should add a store property to sessions that'll store the session in redis or mongo. See the express-session documentation to learn more.

MAKE SURE TO JOIN THE SLACK AND DISCORD COMMUNITIES AT DEVNURSERY.COM
