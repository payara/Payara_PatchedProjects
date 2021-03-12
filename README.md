# This Repository is now Read Only (Deprecated)
New (and new versions of) Artifacts should now be in payara-artifacts repository in Payara Nexus (https://nexus.payara.fish)
However, existing versions of artifacts will still be in this repository,
so most likely you will need to include both this and the nexus repository in your projects
```
 <repository>
    <id>payara-nexus-artifacts</id>
    <name>Payara Nexus Artifacts</name>
    <url>https://nexus.payara.fish/repository/payara-artifacts</url>
    <releases>
        <enabled>true</enabled>
    </releases>
    <snapshots>
        <enabled>false</enabled>
    </snapshots>
</repository>
```

Deprecated Payara_PatchedProjects
======================

Deprecated - A maven repository containing patched projects used by Payara. 
