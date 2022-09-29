library 'smartlogic-common@v2'

smartlogic([
  docker: 'smartlogic/custom/centos7/kmm.json:master-451',
  builder: smartlogic.YarnBuilder(),
  buildWrapper: {
    sh "chown -R root ./"
    it()
  },
])


