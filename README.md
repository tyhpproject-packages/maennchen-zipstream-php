<!-- tyhp-readme:start -->
# tyhpdef/maennchen-zipstream-php

Tyhp type definitions for `maennchen/zipstream-php` `3.2.2`.

```bash
composer require --dev tyhpdef/maennchen-zipstream-php:3.2.2
```

This is a metapackage. Composer also installs `tyhpdef/maennchen-zipstream-php-impl` (type files).
Require **this** name, not `tyhpdef/maennchen-zipstream-php-impl`.

See https://tyhplang.com.

## Maintain `maennchen/zipstream-php`? Ship the types yourself

If you are a Packagist maintainer of `maennchen/zipstream-php`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/maennchen-zipstream-php-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `maennchen/zipstream-php` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/maennchen-zipstream-php": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `maennchen/zipstream-php` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `maennchen/zipstream-php` with a real constraint,
   `"replace": { "tyhpdef/maennchen-zipstream-php": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `maennchen/zipstream-php` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/maennchen-zipstream-php` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
