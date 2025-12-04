# Chapter 4: First App Deployment with ArgoCD

In this chapter, we will learn how to deploy applications with ArgoCD using **three different approaches**:  

1. **UI Approach** → NGINX example  
2. **CLI Approach** → Apache example  
3. **Declarative Approach** → Online Shop example  

Each method has its use cases, but only the **Declarative approach** aligns with the principles of GitOps.  

---

## Fork and Clone this Git Repository into local system

1. First Fork it into your GitHub Account:

   Go to below url, and fork it:

      ```bash
      https://github.com/vishalgunjalswe/argocd-demos.git
      ```

2. Then clone it, into your Local system

      ```bash
      git clone https://github.com/<your-username>/argocd-demos.git
      ```   

Replace `<your-username>` with your GitHub Username.

This repo contains the manifest files that are need to apply all three approaches

---