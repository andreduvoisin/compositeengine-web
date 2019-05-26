# compositeengine-web

Website for Composite Engine

[compositeengine.com](https://compositeengine.com)

## Production

### ZEIT Now

#### Installing ZEIT Now

https://zeit.co/docs/

#### Deploying

Deploys the current codebase to a ZEIT Now domain:

```
now
```

The domain that is outputted can be tested against.

Aliases the last ZEIT Now domain created to `compositeengine.com`:

```
now alias
```

Therefore, the following will create a domain and alias `compositeengine.com` to that domain, thus deploying to production.

```
now && now alias
```

#### Other Commands

List deployments:

```
now ls
```

Remove all non-aliased deployments (to clean up):

```
now rm <app> --safe
```

## Relevant Links

Zeit: https://zeit.co
