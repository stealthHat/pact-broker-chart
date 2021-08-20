## Pact broker helm chart

* install

  $ helm repo add pact-broker https://stealthhat.github.io/pact-broker-chart/

  $ helm install my-pact-broker pact-broker/pact-broker --version 0.2.0

This chart expect a postgress runnig, pass the auth vars in values.yaml
