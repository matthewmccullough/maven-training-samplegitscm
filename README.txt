This project demonstrates how the <scm> tag of Maven can connect to a Git repository.

You can demonstrate:
mvn release:prepare (if you have checkin permissions, as this PUSHes to your remote repo)
mvn scm:diff (creates a standard UNIX .diff file)
mvn scm:validate
mvn scm:status
mvn scm:tag -Dtag=SOMETAGNAME
mvn scm:changelog

mvn scm:list (does not work on Git right now;NPE)

Source:
https://svn.apache.org/repos/asf/maven/scm/tags/maven-scm-1.1/maven-scm-providers/maven-scm-providers-git/maven-scm-provider-git-commons/src/main/java/org/apache/maven/scm/provider/git/

http://docs.codehaus.org/display/SCM/SCM+Matrix

On the release:perform step, remind students that any reports configured to run will generally be executed.
