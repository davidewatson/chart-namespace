# chart-namespace
This chart creates a [Namespace](
https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/)
and associated [Role-Based Access Control (RBAC)](
https://kubernetes.io/docs/admin/authorization/rbac/) and [Resource Quotas](
https://kubernetes.io/docs/concepts/policy/resource-quotas/).

Each application should have a different
[ServiceAccount](
https://kubernetes.io/docs/tasks/configure-pod-container/configure-service-account/)
and namespace. This is necessary to ensure isolation and enforce the
principle of least privilege.
