# THIS REPO IS OBSOLETE AND HAS BITROTTED

The OpenStax landing page (openstax.org).

* `bundle exec middleman build` to generate the static (compiled) version of the site in the `build` directory
* `bundle exec middleman s3_sync` to deploy to AWS (make sure to have appropriate AWS credentials in a `.s3_sync` file), deploys from `build` directory.
* `bundle exec middleman server` to launch the dev server.
