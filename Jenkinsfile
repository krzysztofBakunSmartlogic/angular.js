library 'smartlogic-common@v2'

smartlogic([
  docker: 'smartlogic/custom/centos7/workbench-build.json-java-corretto-11:master-466',
  builder: smartlogic.yarnBuilder(),
  buildWrapper: {
    sh "chown -R root ./"
    it()
  },
])


