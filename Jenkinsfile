library 'smartlogic-common@v2'

smartlogic([
  docker: 'smartlogic/custom/centos7/angularjs.json-java-oracle:ta13245-fix-visualisation-app-5',
  builder: smartlogic.yarnBuilder(),
  buildWrapper: {
    sh "chown -R root ./"
    it()
  },
])


