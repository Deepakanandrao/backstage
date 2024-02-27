---
'@backstage/plugin-catalog': patch
---

Allow the `spec.target` field to be searchable in the catalog table for locations. Previously, only the `spec.targets` field was be searchable. This makes locations generated by providers such as the `GithubEntityProvider` searchable in the catalog table. [#23098](https://github.com/backstage/backstage/issues/23098)