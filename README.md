# FG-Product-Card

Este es un paquete de pruebas de despliege en NPM

## Fernando Gimeno

### Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'fg-product-card';
```

```
<ProductCard
  product={product}
  initialValues={{ count: 5, maxCount: 10 }}
>
  {
    () => (
    <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons />
    </>
    )
  }
</ProductCard>
```
