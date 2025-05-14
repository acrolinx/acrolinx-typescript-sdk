# Reference

## StyleGuides

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">getStyleGuides</a>() -> unknown</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleGuides.getStyleGuides();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `StyleGuides.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">createStyleGuide</a>() -> unknown</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleGuides.createStyleGuide();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `StyleGuides.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">getStyleGuide</a>(styleGuideId) -> unknown</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleGuides.getStyleGuide("style_guide_id");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**styleGuideId:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StyleGuides.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">updateStyleGuide</a>(styleGuideId) -> unknown</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleGuides.updateStyleGuide("style_guide_id");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**styleGuideId:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StyleGuides.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">deleteStyleGuide</a>(styleGuideId) -> unknown</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleGuides.deleteStyleGuide("style_guide_id");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**styleGuideId:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StyleGuides.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## StyleChecks

<details><summary><code>client.styleChecks.<a href="/src/api/resources/styleChecks/client/Client.ts">createStyleCheck</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleChecks.createStyleCheck({
    document_id: "document_id",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `acrolinx.CreateStyleCheckV1StyleChecksPostRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StyleChecks.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.styleChecks.<a href="/src/api/resources/styleChecks/client/Client.ts">getStyleCheck</a>(workflowId, { ...params }) -> acrolinx.StyleCheckResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleChecks.getStyleCheck("workflow_id", {
    document_id: "document_id",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workflowId:** `string`

</dd>
</dl>

<dl>
<dd>

**request:** `acrolinx.GetStyleCheckV1StyleChecksWorkflowIdGetRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StyleChecks.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## StyleSuggestions

<details><summary><code>client.styleSuggestions.<a href="/src/api/resources/styleSuggestions/client/Client.ts">createStyleSuggestion</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleSuggestions.createStyleSuggestion({
    document_id: "document_id",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `acrolinx.CreateStyleSuggestionV1StyleSuggestionsPostRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StyleSuggestions.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.styleSuggestions.<a href="/src/api/resources/styleSuggestions/client/Client.ts">getStyleSuggestion</a>(workflowId, { ...params }) -> acrolinx.SuggestionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleSuggestions.getStyleSuggestion("workflow_id", {
    document_id: "document_id",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workflowId:** `string`

</dd>
</dl>

<dl>
<dd>

**request:** `acrolinx.GetStyleSuggestionV1StyleSuggestionsWorkflowIdGetRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StyleSuggestions.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## StyleRewrites

<details><summary><code>client.styleRewrites.<a href="/src/api/resources/styleRewrites/client/Client.ts">createStyleRewrite</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleRewrites.createStyleRewrite({
    document_id: "document_id",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `acrolinx.CreateStyleRewriteV1StyleRewritesPostRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StyleRewrites.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.styleRewrites.<a href="/src/api/resources/styleRewrites/client/Client.ts">getStyleRewrite</a>(workflowId, { ...params }) -> acrolinx.RewriteResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleRewrites.getStyleRewrite("workflow_id", {
    document_id: "document_id",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workflowId:** `string`

</dd>
</dl>

<dl>
<dd>

**request:** `acrolinx.GetStyleRewriteV1StyleRewritesWorkflowIdGetRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StyleRewrites.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>
