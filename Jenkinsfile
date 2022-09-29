library 'smartlogic-common@v2'

smartlogic([
  docker: 'smartlogic/custom/centos7/da.json-java-open-11:master-427',
  builder: smartlogic.yarnBuilder(),
  buildWrapper: {
    sh "chown -R root ./"
    it()
  },
])


