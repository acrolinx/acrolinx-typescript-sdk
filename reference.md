# Reference

## Style Guides

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">getStyleGuides</a>({ ...params }) -> acrolinx.StyleGuideResponse[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get all style guides.

</dd>
</dl>
</dd>
</dl>

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

**request:** `acrolinx.StyleGuidesGetStyleGuidesRequest`

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

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">createStyleGuide</a>(file_upload, { ...params }) -> acrolinx.StyleGuideResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleGuides.createStyleGuide(fs.createReadStream("/path/to/your/file"), {});
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

**file_upload:** `File | fs.ReadStream | Blob`

</dd>
</dl>

<dl>
<dd>

**request:** `acrolinx.StyleGuideRequestBody`

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

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">getStyleGuide</a>(styleGuideId) -> acrolinx.StyleGuideResponse</code></summary>
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

**styleGuideId:** `string` — The ID of the style guide.

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

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">deleteStyleGuide</a>(styleGuideId) -> void</code></summary>
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

**styleGuideId:** `string` — The ID of the style guide.

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

<details><summary><code>client.styleGuides.<a href="/src/api/resources/styleGuides/client/Client.ts">updateStyleGuide</a>(styleGuideId, { ...params }) -> acrolinx.StyleGuideResponse</code></summary>
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

**styleGuideId:** `string` — The ID of the style guide.

</dd>
</dl>

<dl>
<dd>

**request:** `acrolinx.BodyStyleGuidesUpdateStyleGuide`

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

## Style Checks

<details><summary><code>client.styleChecks.<a href="/src/api/resources/styleChecks/client/Client.ts">createStyleCheck</a>(file_upload, { ...params }) -> acrolinx.WorkflowResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Start a style and brand check run. Returns a workflow ID for each file.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleChecks.createStyleCheck(fs.createReadStream("/path/to/your/file"), {});
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

**file_upload:** `File | fs.ReadStream | Blob`

</dd>
</dl>

<dl>
<dd>

**request:** `acrolinx.StyleChecksCreateStyleCheckRequest`

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

<details><summary><code>client.styleChecks.<a href="/src/api/resources/styleChecks/client/Client.ts">getStyleCheck</a>(workflowId) -> acrolinx.StyleChecksGetStyleCheckResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

get the results of a style and brand check run.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleChecks.getStyleCheck("workflow_id");
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

**requestOptions:** `StyleChecks.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## Style Suggestions

<details><summary><code>client.styleSuggestions.<a href="/src/api/resources/styleSuggestions/client/Client.ts">createStyleSuggestion</a>(file_upload, { ...params }) -> acrolinx.WorkflowResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Start a style and brand suggestion run. Returns a workflow ID for each file.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleSuggestions.createStyleSuggestion(fs.createReadStream("/path/to/your/file"), {});
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

**file_upload:** `File | fs.ReadStream | Blob`

</dd>
</dl>

<dl>
<dd>

**request:** `acrolinx.StyleSuggestionsCreateStyleSuggestionRequest`

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

<details><summary><code>client.styleSuggestions.<a href="/src/api/resources/styleSuggestions/client/Client.ts">getStyleSuggestion</a>(workflowId) -> acrolinx.StyleSuggestionsGetStyleSuggestionResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the results of a suggestion run.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleSuggestions.getStyleSuggestion("workflow_id");
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

**requestOptions:** `StyleSuggestions.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## Style Rewrites

<details><summary><code>client.styleRewrites.<a href="/src/api/resources/styleRewrites/client/Client.ts">createStyleRewrite</a>(file_upload, { ...params }) -> acrolinx.WorkflowResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Start a rewrite run for one or many files. Returns a workflow ID for each file.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleRewrites.createStyleRewrite(fs.createReadStream("/path/to/your/file"), {});
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

**file_upload:** `File | fs.ReadStream | Blob`

</dd>
</dl>

<dl>
<dd>

**request:** `acrolinx.StyleRewritesCreateStyleRewriteRequest`

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

<details><summary><code>client.styleRewrites.<a href="/src/api/resources/styleRewrites/client/Client.ts">getStyleRewrite</a>(workflowId) -> acrolinx.RewriteResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the results of a rewrite run.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.styleRewrites.getStyleRewrite("workflow_id");
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

**requestOptions:** `StyleRewrites.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>
