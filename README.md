# Source: tnf/charts/kyc-client-onboarding/templates/secrets.yaml
apiVersion: v1
kind: Secret
metadata:
    name: kyc-client-onboarding-secret
    labels:
        app.kubernetes.io/name: kyc-client-onboarding-kyc-client-onboarding
        helm.sh/chart: kyc-client-onboarding-0.3.2
        app.kubernetes.io/managed-by: Helm
        app.kubernetes.io/instance: kyc-client-onboarding
        app.kubernetes.io/version: 1.16.0
        meta.helm.sh/release-name: kyc-client-onboarding
        meta.helm.sh/release-namespace: kyc
        app.kubernetes.io/component: backend-golang-kyc-client-onboarding
type: Opaque
stringData:
    .env: |-

