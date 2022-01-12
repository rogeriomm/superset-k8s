# Install
```shell
kubect create namespace superset
cd install
helm upgrade --install --namespace superset --values values.yaml superset superset/superset
```

   * http://superset.worldl.xpt
      * User: admin
      * Password: admin

# Uninstall
```shell
helm uninstall  --namespace superset superset
kubect delete namespace superset
```

# References
   * https://superset.apache.org/docs/installation/running-on-kubernetes: Running on Kubernetes
   * https://medium.com/@nileshxbhosale/apache-superset-a-cost-effective-alternative-to-quick-sight-for-data-lake-668868fe51c7
      * https://superset.apache.org/docs/intro
