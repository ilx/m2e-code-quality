
    mvn -X org.eclipse.tycho:tycho-versions-plugin:0.15.0:set-version -DnewVersion=1.1.0

    mvn -X -pl com.basistech.m2e.code.quality.checkstyle.feature -am package 

    mvn -X -pl com.basistech.m2e.code.quality.site -am package

