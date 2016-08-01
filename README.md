# fake vulnerabilities javascript npm
Example npm repository containing fake data with vulnerable dependencies

It should report at least:
 CVE-2015-8315 in module "ms" (https://nodesecurity.io/advisories/46)

    $ nsp check --output summary
    (+) 1 vulnerabilities found
     Name   Installed   Patched   Path                                      More Info
     ms     0.7.0       >0.7.0    example-npm-javascript@0.0.1 > ms@0.7.0   https://nodesecurity.io/advisories/46
