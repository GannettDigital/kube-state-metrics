# Endpoint Metrics

| Metric name| Metric type | Labels/tags |
| ---------- | ----------- | ----------- |
| kube_endpoint_address_not_ready | Gauge | `endpoint`=&lt;endpoint-name&gt; <br> `namespace`=&lt;endpoint-namespace&gt; |
| kube_endpoint_address_available | Gauge | `endpoint`=&lt;endpoint-name&gt; <br> `namespace`=&lt;endpoint-namespace&gt; |
| kube_endpoint_info | Gauge | `endpoint`=&lt;endpoint-name&gt; <br> `namespace`=&lt;endpoint-namespace&gt;  |
| kube_endpoint_labels | Gauge | `endpoint`=&lt;endpoint-name&gt; <br> `namespace`=&lt;endpoint-namespace&gt; <br> `label_endpoint_LABEL`=&lt;endpoint_LABEL&gt;  |
| kube_endpoint_created | Gauge | `endpoint`=&lt;endpoint-name&gt; <br> `namespace`=&lt;endpoint-namespace&gt; |