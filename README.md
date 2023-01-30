# essais-automatises

## k6

```bash
kubectl testkube create test --file script.js --name k6-test
```

## Postman

```bash
kubectl testkube create test --name postman-echo --file API-Tests.postman_collection.json --type postman/collection
```

## Cypress

```bash
kubectl testkube create test --git-uri https://github.com/kubeshop/testkube-executor-cypress.git --git-branch main --git-path examples --name kubeshop-cypress --type cypress/project
```