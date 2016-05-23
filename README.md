# packer\_product\_eurostar

*This repo does nothing by itself - it is expected to be cloned
within a project's own checkout, along with the repo _packer_includes_.

It contains assets used to take a base ami (see packer_monlog_*)
and install a product on it - common to all products, not just those
that are puppet-configured.

It *is* responsible for the creation of the info files under
/etc/eurostar used by cloud-init (and startup scripts) to discover things
about this instance and the eurostar ecosystem.

*ADD STUFF TO THIS LAYER TO DO WITH INSTALLING AND CONFIGURING THE APPS*


