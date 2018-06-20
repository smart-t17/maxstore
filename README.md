# maxstore - Ecommerce Progressive Web Apps

maxstore is React and Node.js based eCommerce platform. Allows creating a Progressive Web Apps.

Built with:
* Node.js v8.9
* React v16
* Redux
* Express
* Babel
* WebPack 4
* MongoDB

## Dashboard
Client-side dashboard use JSON Web Token (JWT) to access REST API.

![maxstore Dashboard](https://maxstore.com/assets/images/maxstore-dashboard-products.png?)

![Signin email](https://maxstore.com/assets/images/maxstore-signin-email.png)

## Store
Single-Page Application with React server-side rendering. [Demo store](https://store.maxstore.com)

[![maxstore Store](https://maxstore.com/assets/images/maxstore-mobile-product.png)](https://store.maxstore.com)

[![maxstore Store](https://maxstore.com/assets/images/maxstore-mobile-order-summary.png)](https://store.maxstore.com)

## Installation

- [with GitHub](https://github.com/maxstore/maxstore/blob/master/docs/getting-started.md)
- [with Docker](https://github.com/maxstore/maxstore/blob/master/docs/getting-started-docker.md)
- [How to deploy a maxstore on Ubuntu 16.04](https://github.com/maxstore/maxstore/blob/master/docs/how-to-deploy-a-maxstore-on-ubuntu-16-04.md)

### Requirements
* Node.js >= 8
* MongoDB >= 3.2


## Documentation

[Documentation](https://github.com/smartmaxdev/maxstore/tree/master/docs)


## Application Structure

```
.
├── config                   # Project and build configurations
├── dist                     # Distribution folder
├── locales                  # Text files
├── logs                     # Log files
├── public                   # Static public assets and uploads
│   ├── admin                # Dashboard index.html
│   ├── admin-assets         # Dashboard assets
│   └── content              # Store root folder
|
├── scripts                  # Shell scripts for theme install/export
├── src                      # Application source code
│   ├── admin                # Dashboard application
│   │   └── client           # Client side code
│   ├── api                  # REST API
│   │   └── server           # Server side code
│   ├── store                # Store application
│   |   ├── client             # Client side code
│   |   ├── server             # Server side code
│   |   └── shared             # Universal code
│   └── index.js             # Server application start point
├── theme                    # Theme as a local package
└── process.json             # pm2 process file
```


## Sponsoring

maxstore is an MIT-licensed open source project. It's an independent project with ongoing development made possible thanks to the support of these awesome backers. [Become a backer or sponsor on OpenCollective](https://opencollective.com/maxstore).

### Sponsors

[Become a sponsor](https://opencollective.com/maxstore#sponsor) and get your logo on our README on Github and [maxstore.com](https://maxstore.com) with a link to your site.

<a href="https://opencollective.com/maxstore/tiers/sponsor/1/website" rel="noopener" target="_blank" style="margin-right: 8px;">
<img src="https://opencollective.com/maxstore/tiers/sponsor/1/avatar.svg" alt="0" /></a>
<a href="https://opencollective.com/maxstore/tiers/sponsor/2/website" rel="noopener" target="_blank" style="margin-right: 8px;">
<img src="https://opencollective.com/maxstore/tiers/sponsor/2/avatar.svg" alt="0" /></a>
<a href="https://opencollective.com/maxstore/tiers/sponsor/0/website" rel="noopener" target="_blank" style="margin-right: 8px;">
<img src="https://opencollective.com/maxstore/tiers/sponsor/0/avatar.svg" alt="0" /></a>


## Contributing

If you can, please contribute by reporting issues, discussing ideas, or submitting pull requests with patches and new features. We do our best to respond to all issues and pull requests within a day or two, and make patch releases to npm regularly.


## Licence

This software is provided free of charge and without restriction under the MIT License
