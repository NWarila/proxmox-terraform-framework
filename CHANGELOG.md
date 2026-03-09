# Changelog

## [2.0.0](https://github.com/NWarila/proxmox-terraform-framework/compare/v1.0.1...v2.0.0) (2026-03-09)


### ⚠ BREAKING CHANGES

* user_account removed from initialization block in tfvars. Inject credentials via TF_VAR_proxmox_cloud_init_user_name, TF_VAR_proxmox_cloud_init_user_password, and TF_VAR_proxmox_cloud_init_user_public_key environment variables.

### Features

* add .gitattributes for consistent line endings and language detection ([481e23f](https://github.com/NWarila/proxmox-terraform-framework/commit/481e23f6c6ad6e2328619d0d64dd5e3887c24fb2))
* enhance network device configuration with optional IPv4 prefix length ([1ca66fe](https://github.com/NWarila/proxmox-terraform-framework/commit/1ca66fef80fe0db0be03025fa052e38af35e022c))
* implement dynamic initialization properties for virtual machines ([6d53576](https://github.com/NWarila/proxmox-terraform-framework/commit/6d535765df83c3ef35f40bbfca60dff595b25fde))
* move cloud-init credentials to top-level sensitive variables ([d44ed6b](https://github.com/NWarila/proxmox-terraform-framework/commit/d44ed6bd7296fc8a0c171558b5cacc03f95bb683))

## [1.0.1](https://github.com/NWarila/proxmox-terraform-framework/compare/v1.0.0...v1.0.1) (2026-03-09)


### Bug Fixes

* secure TLS default and document proxmox_skip_tls_verify ([fe7cc5f](https://github.com/NWarila/proxmox-terraform-framework/commit/fe7cc5fef13f91df0f2936227014a823224910e8))

## 1.0.0 (2026-03-09)


### Bug Fixes

* correct pip cache path and release-please action ref ([5f2cb69](https://github.com/NWarila/proxmox-terraform-framework/commit/5f2cb697f8d0cb9162c13e5fdc232c3a8bb8d9fa))
