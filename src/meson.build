executable('spnavcfg',
           'main.c',
           dependencies: [
             dependency('gtk+-2.0'),
             dependency('gmodule-export-2.0'),
             dependency('x11'),
             dependency('spnav')
           ],
           c_args: [ '-DPKGDATADIR="@0@"'.format(pkgdatadir) ],
           install : true)


