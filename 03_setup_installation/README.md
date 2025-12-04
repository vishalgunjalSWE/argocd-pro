# ArgoCD Setup and Installation

Let's see how we can Setup & Install ArgoCD (UI and CLI) and access via the browser.

---

# Prerequisites

Before starting, ensure you have the following installed on your system:

1. **Docker** → Required for Kind to run containers as cluster nodes.

   ```bash
   sudo apt-get update
   sudo apt install docker.io -y
   sudo usermod -aG docker $USER && newgrp docker
   docker --version

   docker ps
   ```

2. **Kind (Kubernetes in Docker)** → To create the cluster.

   ```bash
   kind version
   ```

   [Install Guide](https://kind.sigs.k8s.io/docs/user/quick-start/#installation)

3. **kubectl** → To interact with the cluster.

   ```bash
   kubectl version --client
   ```

   [Install Guide](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

4. **Helm (for Helm-based installation)**

   ```bash
   helm version
   ```

   [Install Guide](https://helm.sh/docs/intro/install/)

---