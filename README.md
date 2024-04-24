# kustomize-exercise

- [kustomize 사용 예제](https://kubernetes.io/ko/docs/tasks/manage-kubernetes-objects/kustomization/)

## 1. configMapGenerator

### 1.1 cmg_01

```sh
cd 01_configmapGenerator/;
kubectl kustomize ./cmg_01;
```

### 1.2 cmg_02

```sh
cd 01_configmapGenerator/;
kubectl kustomize ./cmg_02;
```

### 1.3 cmg_03

```sh
cd 01_configmapGenerator/;
kubectl kustomize ./cmg_03;
```

### 1.4 cmg_04

```sh
cd 01_configmapGenerator/;
kubectl kustomize ./cmg_04;
```

## 2. secretGenerator

### 2.1 sg_01

```sh
cd 02_secretGenerator/;
kubectl kustomize ./sg_01;
```

### 2.2 sg_02

```sh
cd 02_secretGenerator/;
kubectl kustomize ./sg_02;
```

### 2.3 sg_03

```sh
cd 02_secretGenerator/;
kubectl kustomize ./sg_03;
```

## 3. generatorOptions

### 3.1 go_01

```sh
cd 03_generatorOptions/;
kubectl kustomize ./go_01;
```

## 4. Setting cross-cutting fields

### 4.1 ccf_01

```sh
cd 04_Setting_cross_cutting_fields;
kubectl kustomize ./ccf_01;
```

## 5. Composing and Customizing Resources

### 5.1 Composing (ccr_01)

```sh
cd 05_Composing_Customizing_Resources;
kubectl kustomize ./ccr_01;
```

### 5.2 Customizing (ccr_02)

```sh
cd 05_Composing_Customizing_Resources;
kubectl kustomize ./ccr_02;
```

### 5.3 Customizing (ccr_03)

```sh
cd 05_Composing_Customizing_Resources;
kubectl kustomize ./ccr_03;
```

### 5.4 Customizing (ccr_04)

```sh
cd 05_Composing_Customizing_Resources;
kubectl kustomize ./ccr_04;
```

### 5.5 Customizing (ccr_05)

```sh
cd 05_Composing_Customizing_Resources;
kubectl kustomize ./ccr_05;
```

## 6. Bases and Overlays

### 6.1 dev

```sh
cd 06_Bases_Overlays;
kubectl kustomize ./dev;
```

### 6.2 prod

```sh
cd 06_Bases_Overlays;
kubectl kustomize ./prod;
```
