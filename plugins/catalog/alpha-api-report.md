## API Report File for "@backstage/plugin-catalog"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { BackstagePlugin } from '@backstage/frontend-plugin-api';
import { Extension } from '@backstage/frontend-plugin-api';
import { TranslationRef } from '@backstage/core-plugin-api/alpha';

// @alpha (undocumented)
export const CatalogApi: Extension<{}>;

// @alpha (undocumented)
export const catalogTranslationRef: TranslationRef<
  'catalog',
  {
    readonly catalog_page_title: '{{orgName}} Catalog';
    readonly catalog_page_create_button_title: 'Create';
  }
>;

// @alpha (undocumented)
const _default: BackstagePlugin;
export default _default;

// @alpha (undocumented)
export const StarredEntitiesApi: Extension<{}>;

// (No @packageDocumentation comment for this package)
```
