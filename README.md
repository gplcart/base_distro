A Composer meta package to install the [Base installation profile](https://github.com/gplcart/base) and all its required modules

**Usage:**

Make `test` installation directory in `your-domain.com` web directory:

    composer create-project gplcart/base_distro test --no-interaction

then run web installer at `http://your-domain.com/test` OR execute the command:

    cd test
    php gplcart install