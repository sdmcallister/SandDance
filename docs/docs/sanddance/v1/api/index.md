---
layout: api
---

# sanddance

## Functions

### use

Specify the dependency libraries to use for rendering.

```typescript
function use(vega: VegaBase, deck: DeckBase, layers: DeckLayerBase, luma: LumaBase): void;
```

**Parameters**

| Name   | Type                                     | Description          |
| ------ | ---------------------------------------- | -------------------- |
| vega   | [VegaBase][InterfaceDeclaration-42]      | Vega library.        |
| deck   | [DeckBase][InterfaceDeclaration-43]      | deck/core library.   |
| layers | [DeckLayerBase][InterfaceDeclaration-44] | deck/layers library. |
| luma   | [LumaBase][InterfaceDeclaration-45]      | luma.gl library.     |

**Return type**

void

## Classes

### [Viewer][ClassDeclaration-5]

Component to view a SandDance data visualization.


## Namespaces

### [constants][NamespaceImport-0]


----------

### [searchExpression][NamespaceImport-1]


----------

### [types][NamespaceImport-2]


----------

### [util][NamespaceImport-3]


----------

### [VegaDeckGl][NamespaceImport-4]


## Variables

### colorSchemes

Array of color schemes.

```typescript
const colorSchemes: ColorScheme[];
```

**Type**

[ColorScheme][InterfaceDeclaration-0][]

[SourceFile-0]: index#indexts
[FunctionDeclaration-3]: index#use
[InterfaceDeclaration-42]: vegadeckgl/types#vegabase
[InterfaceDeclaration-43]: vegadeckgl/types#deckbase
[InterfaceDeclaration-44]: vegadeckgl/types#decklayerbase
[InterfaceDeclaration-45]: vegadeckgl/types#lumabase
[ClassDeclaration-5]: viewer#viewer
[NamespaceImport-0]: constants#constants
[NamespaceImport-1]: searchexpression#searchexpression
[NamespaceImport-2]: types#types
[NamespaceImport-3]: util#util
[NamespaceImport-4]: vegadeckgl#vegadeckgl
[VariableDeclaration-0]: index#colorschemes
[InterfaceDeclaration-0]: types#colorscheme