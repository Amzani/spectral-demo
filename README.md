# Spectral Demo

## 1. The bare miniumum

```
echo 'extends: spectral:oas' > .spectral.yaml
spectral lint openapi.yaml
```

## 2. Customize

Let's turn off some rules

```
spectral lint openapi.yaml -r spectral-2.yaml
```

## 3. I don't like Camels

```
spectral lint openapi.yaml -r spectral-3.yaml
```

## 4. I want to Enforce service tier in endpoints

```
spectral lint openapi.yaml -r spectral-4.yaml
```
