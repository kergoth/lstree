Print a directory tree using indent for depth, but unlike the 'tree'
command, shows no ascii/utf8 lines. This format is useful for dumping the
tree in a form which is pleasant to edit in a text editor, e.g. for
reviewing/auditing a directory tree, file by file.

Example:

    $ lstree conf classes
    conf/
        bblayers.conf.sample
        distro/
            mel-tiny.conf
            include/
                expandvars.inc
                toolchain-sanity.inc
                mel-versions.conf
                mel.conf
                mel-providers.conf
                mel-vardeps.conf
                sstate.inc
                kernel-link.inc
            mel.conf
        machine/
            include/
                tune-ppce300c3.inc
                imx-base.inc
        local.conf.sample
        layer.conf
    classes/
        kernel-lttng.bbclass
        base.bbclass
        kernel.bbclass
        buildstats-summary.bbclass
        package.bbclass
        cml1.bbclass
        mirrors.bbclass
        sstate-reuse.bbclass
        user_features.bbclass
        cml1-merge.bbclass
        isolated-sstate-dir.bbclass
        copyleft_compliance.bbclass
        package_early_expand.bbclass
        license.bbclass
        deploy-license-manifest.bbclass
