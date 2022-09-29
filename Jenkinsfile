library 'smartlogic-common@v2'

smartlogic([
  docker: 'smartlogic/custom/centos7/blackduck-scan.json-java-open-11:master-468',
  builder: smartlogic.yarnBuilder(),
  buildWrapper: {
    sh "chown -R root ./"
    it()
  },
])


