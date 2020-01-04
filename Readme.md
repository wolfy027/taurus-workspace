Taurus Configurations:
    1. Taurus Base Configs
    2. User Config(~/.bzt-rc)
    3. Merge in Test Files and Overrides

Command Line ovverrides   [-o]
    bzt my.yml -o modules.jmeter.path=alternate/jmeter/path

Jmeter Module Settings
<p>
#modules:
#  jmeter:
#    properties:  # JMeter properties for every JMeter run
#      prop_name: prop value
#    system-properties:  # Java system properties
#      sun.net.http.allowRestrictedHeaders: "true"
#    memory-xmx: 4G  # allow JMeter to use up to 4G of memory
#    path: ~/.bzt/jmeter-taurus/{version}/bin/jmeter  # path to local jmeter installation
#    version: 3.2  # version to use
#    plugins:  # plugins to install
#    - jpgc-json=2.2
#    - jmeter-ftp
#    - jpgc-casutg
</p>