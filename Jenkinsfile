library 'smartlogic-common@v2'

smartlogic([
  docker: 'node:lts-alpine',
  builder: smartlogic.yarnBuilder(),
  buildWrapper: {
    sh "chown -R root ./"
    it()
  },
])


