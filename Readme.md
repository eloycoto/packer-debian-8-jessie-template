Debian 8 vmware template
========================

This template is my personal debian 8 configuration, based on
[tech-angels/packer-templates](https://github.com/tech-angels/packer-templates),
but with the following changes:

- I'm using debian 8 instead 7.
- Keyboard is en_gb
- I'm only build debian templates for vmware.


### Build

To build this project you only need to do the following:

```
packer buuld debian-8-jessie.json
```

### Prerequisites

- [Packer](http://www.packer.io/downloads.html) >= 0.8
- [Vmware fushion](http://www.vmware.com/products/fusion/),
  [workstation](http://www.vmware.com/products/workstation) or
  [player](http://www.vmware.com/products/player/)


