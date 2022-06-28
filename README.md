# DevOps Bootcamp példa alkalmazás leírók

OpenShift leírók a példa alkalmazás kitelepítéséhez.

Az alkalmazás kitelepül Deploymentként, készül hozzá egy Service és egy Route, hogy kívülről is elérhető legyen.

A deployment.yaml fájlban a spec.template.spec.containers[0].image helyen lévő placeholder értéket (INSERT IMAGE NAME HERE) be kell helyettesíteni a buildelt image nevére (repository-val és taggel együtt).
