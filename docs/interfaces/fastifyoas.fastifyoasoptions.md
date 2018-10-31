[fastify-oas](../README.md) > [fastifyOAS](../modules/fastifyoas.md) > [FastifyOASOptions](../interfaces/fastifyoas.fastifyoasoptions.md)

# Interface: FastifyOASOptions

Fastify OAS plugin options

## Type parameters
#### Query 
#### Params 
#### Headers 
#### Body 
## Hierarchy

 `RegisterOptions`<`Server`, `IncomingMessage`, `ServerResponse`>

**↳ FastifyOASOptions**

## Indexable

\[key: `string`\]:&nbsp;`any`
Fastify OAS plugin options

## Index

### Properties

* [addModels](fastifyoas.fastifyoasoptions.md#addmodels)
* [beforeHandler](fastifyoas.fastifyoasoptions.md#beforehandler)
* [bodyLimit](fastifyoas.fastifyoasoptions.md#bodylimit)
* [config](fastifyoas.fastifyoasoptions.md#config)
* [exposeRoute](fastifyoas.fastifyoasoptions.md#exposeroute)
* [logLevel](fastifyoas.fastifyoasoptions.md#loglevel)
* [openapi](fastifyoas.fastifyoasoptions.md#openapi)
* [prefix](fastifyoas.fastifyoasoptions.md#prefix)
* [routePrefix](fastifyoas.fastifyoasoptions.md#routeprefix)
* [schema](fastifyoas.fastifyoasoptions.md#schema)
* [schemaCompiler](fastifyoas.fastifyoasoptions.md#schemacompiler)
* [swagger](fastifyoas.fastifyoasoptions.md#swagger)
* [yaml](fastifyoas.fastifyoasoptions.md#yaml)

---

## Properties

<a id="addmodels"></a>

###  addModels

**● addModels**: *`Boolean`*

*Defined in lib/index.d.ts:104*

If `true` adds fastify schemas as openapi models
*__default__*: false

___
<a id="beforehandler"></a>

### `<Optional>` beforeHandler

**● beforeHandler**: * `FastifyMiddleware`<`Server`, `IncomingMessage`, `ServerResponse`, `Query`, `Params`, `Headers`, `Body`> &#124; `Array`<`FastifyMiddleware`<`Server`, `IncomingMessage`, `ServerResponse`, `Query`, `Params`, `Headers`, `Body`>>
*

*Inherited from RouteShorthandOptions.beforeHandler*

*Defined in node_modules/fastify/fastify.d.ts:169*

___
<a id="bodylimit"></a>

### `<Optional>` bodyLimit

**● bodyLimit**: *`number`*

*Inherited from RouteShorthandOptions.bodyLimit*

*Defined in node_modules/fastify/fastify.d.ts:173*

___
<a id="config"></a>

### `<Optional>` config

**● config**: *`any`*

*Inherited from RouteShorthandOptions.config*

*Defined in node_modules/fastify/fastify.d.ts:175*

___
<a id="exposeroute"></a>

###  exposeRoute

**● exposeRoute**: *`Boolean`*

*Defined in lib/index.d.ts:99*

If `true` the plugin will expose the documentation routes
*__default__*: false

___
<a id="loglevel"></a>

### `<Optional>` logLevel

**● logLevel**: *`string`*

*Inherited from RouteShorthandOptions.logLevel*

*Defined in node_modules/fastify/fastify.d.ts:174*

___
<a id="openapi"></a>

###  openapi

**● openapi**: *`String`*

*Defined in lib/index.d.ts:109*

Openapi version
*__default__*: 3.0.0

___
<a id="prefix"></a>

### `<Optional>` prefix

**● prefix**: *`string`*

*Inherited from RegisterOptions.prefix*

*Defined in node_modules/fastify/fastify.d.ts:200*

___
<a id="routeprefix"></a>

###  routePrefix

**● routePrefix**: *`String`*

*Defined in lib/index.d.ts:94*

Documentation endpoint
*__default__*: /documentation

___
<a id="schema"></a>

### `<Optional>` schema

**● schema**: *`RouteSchema`*

*Inherited from RouteShorthandOptions.schema*

*Defined in node_modules/fastify/fastify.d.ts:168*

___
<a id="schemacompiler"></a>

### `<Optional>` schemaCompiler

**● schemaCompiler**: *`SchemaCompiler`*

*Inherited from RouteShorthandOptions.schemaCompiler*

*Defined in node_modules/fastify/fastify.d.ts:172*

___
<a id="swagger"></a>

###  swagger

**● swagger**: *[OpenApiSpec](fastifyoas.openapispec.md)*

*Defined in lib/index.d.ts:118*

OpenApi/Swagger object except paths

___
<a id="yaml"></a>

###  yaml

**● yaml**: *`Boolean`*

*Defined in lib/index.d.ts:114*

If `true` returns yaml instead of json
*__default__*: false

___
