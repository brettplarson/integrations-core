# CHANGELOG - Argo CD

<!-- towncrier release notes start -->

## 2.4.0 / 2024-03-22

***Added***:

* Collect 'argocd_app_labels' for ArgoCD metric ([#16897](https://github.com/DataDog/integrations-core/pull/16897))

***Fixed***:

* Rename Go inuse_use metric to the correct inuse_bytes name ([#17252](https://github.com/DataDog/integrations-core/pull/17252))

## 2.3.0 / 2024-02-16 / Agent 7.52.0

***Added***:

* Update the configuration file to include the new oauth options parameter ([#16835](https://github.com/DataDog/integrations-core/pull/16835))

## 2.2.0 / 2024-01-05 / Agent 7.51.0

***Added***:

* Bump the Python version from py3.9 to py3.11 ([#15997](https://github.com/DataDog/integrations-core/pull/15997))

## 2.1.0 / 2023-09-29 / Agent 7.49.0

***Added***:

* Collect metrics for ArgoCD ApplicationSet ([#15308](https://github.com/DataDog/integrations-core/pull/15308)) Thanks [smartfin](https://github.com/smartfin).

## 2.0.0 / 2023-08-10 / Agent 7.48.0

***Changed***:

* Bump the minimum base check version ([#15427](https://github.com/DataDog/integrations-core/pull/15427))

***Added***:

* Update generated config models ([#15212](https://github.com/DataDog/integrations-core/pull/15212))

***Fixed***:

* Fix types for generated config models ([#15334](https://github.com/DataDog/integrations-core/pull/15334))

## 1.2.0 / 2023-07-10 / Agent 7.47.0

***Added***:

* Add ArgoCD notifications controller metrics ([#14690](https://github.com/DataDog/integrations-core/pull/14690)) Thanks [maxknee](https://github.com/maxknee).

***Fixed***:

* Bump Python version from py3.8 to py3.9 ([#14701](https://github.com/DataDog/integrations-core/pull/14701))

## 1.1.0 / 2023-05-26 / Agent 7.46.0

***Added***:

* Add an ignore_connection_errors option to the openmetrics check ([#14504](https://github.com/DataDog/integrations-core/pull/14504))

***Fixed***:

* Update minimum datadog base package version ([#14463](https://github.com/DataDog/integrations-core/pull/14463))
* Deprecate `use_latest_spec` option ([#14446](https://github.com/DataDog/integrations-core/pull/14446))

## 1.0.1 / 2022-12-09 / Agent 7.42.0

***Fixed***:

* Fix error that was triggered by including configuration parameters not ending in `_endpoint` ([#13409](https://github.com/DataDog/integrations-core/pull/13409))

## 1.0.0 / 2022-11-16

***Added***:

* Argo CD Integration ([#13223](https://github.com/DataDog/integrations-core/pull/13223))
