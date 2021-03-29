# compositeengine-web

Website for [Composite Engine](https://git.io/CompositeEngine)

[compositeengine.com](https://compositeengine.com)

## Vercel

### Installing Vercel

https://vercel.com/docs

### Deploying

To make a preview deployment against the current codebase:
```
vercel
```
The domain that is outputted can be tested against.

To make a production deployment against the current codebase:
```
vercel --prod
```

https://vercel.com/docs/platform/deployments#vercel-cli

### Other Commands

List deployments:
```
vercel ls
```

List deployments for this project:
```
vercel ls compositeengine-web
```

Safely remove unused deployments (to clean up):
```
vercel rm compositeengine-web --safe
```

Vercel will automatically keep deployments for various reasons:

> NOTE: Deployments that are not actively receiving any traffic do not generate any costs nor count towards any limits.
>
> Deleting this deployment will prevent you from instantly reverting and might break links used in integrations, such as the ones in the pull requests of your Git provider.
