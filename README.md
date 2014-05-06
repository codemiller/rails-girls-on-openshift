## Rails Girls app on OpenShift

This repo shows the [Rails Girls application](http://guides.railsgirls.com/app) with the changes required to run on Red Hat's OpenShift Online Platform As A Service.

This is an end result of following the instructions at http://guides.railsgirls.com/openshift.

To get this app running on OpenShift, [sign up for OpenShift Online](https://openshift.redhat.com/app/account/new?web_user[promo_code]=railsgirls), [install the RHC command line tools](https://www.openshift.com/developers/rhc-client-tools-install), and run the following commands:

    rhc setup
    rhc app create openshiftapp ruby-1.9 postgresql-9.2 --from-code=https://github.com/codemiller/rails-girls-on-openshift.git 


