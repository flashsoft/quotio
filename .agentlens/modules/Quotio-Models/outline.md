# Outline

[← Back to MODULE](MODULE.md) | [← Back to INDEX](../../INDEX.md)

Symbol maps for 3 large files in this module.

## Quotio/Models/CustomProviderModels.swift (623 lines)

| Line | Kind | Name | Visibility |
| ---- | ---- | ---- | ---------- |
| 14 | enum | CustomProviderType | (internal) |
| 148 | fn | normalizedStoredBaseURL | (internal) |
| 169 | fn | apiBaseURL | (internal) |
| 176 | fn | modelsEndpointURL | (internal) |
| 187 | struct | CustomAPIKeyEntry | (internal) |
| 218 | struct | ModelMapping | (internal) |
| 245 | struct | CustomHeader | (internal) |
| 264 | struct | CustomProvider | (internal) |
| 317 | method | init | (internal) |
| 334 | fn | encode | (internal) |
| 352 | fn | validate | (internal) |
| 390 | mod | extension CustomProvider | (internal) |
| 404 | fn | toYAMLBlock | (internal) |
| 418 | fn | generateOpenAICompatibilityYAML | (private) |
| 449 | fn | generateClaudeCompatibilityYAML | (private) |
| 480 | fn | generateGeminiCompatibilityYAML | (private) |
| 503 | fn | generateCodexCompatibilityYAML | (private) |
| 522 | fn | generateGlmCompatibilityYAML | (private) |
| 544 | fn | appendHeadersYAML | (private) |
| 563 | fn | escapeYAMLString | (private) |
| 575 | fn | toYAMLSections | (internal) |

## Quotio/Models/MenuBarSettings.swift (632 lines)

| Line | Kind | Name | Visibility |
| ---- | ---- | ---- | ---------- |
| 13 | mod | extension String | (internal) |
| 17 | fn | masked | (internal) |
| 38 | fn | masked | (internal) |
| 46 | struct | MenuBarQuotaItem | (internal) |
| 70 | enum | AppearanceMode | (internal) |
| 97 | class | AppearanceManager | (internal) |
| 112 | method | init | (private) |
| 119 | fn | applyAppearance | (internal) |
| 134 | enum | MenuBarColorMode | (internal) |
| 151 | enum | QuotaDisplayMode | (internal) |
| 165 | fn | displayValue | (internal) |
| 183 | enum | QuotaDisplayStyle | (internal) |
| 210 | enum | RefreshCadence | (internal) |
| 253 | enum | TotalUsageMode | (internal) |
| 270 | enum | ModelAggregationMode | (internal) |
| 286 | mod | extension MenuBarSettingsManager | (internal) |
| 334 | fn | calculateTotalUsagePercent | (internal) |
| 359 | fn | aggregateModelPercentages | (internal) |
| 376 | class | RefreshSettingsManager | (internal) |
| 394 | method | init | (private) |
| 404 | struct | MenuBarQuotaDisplayItem | (internal) |
| 423 | class | MenuBarSettingsManager | (internal) |
| 515 | method | init | (private) |
| 553 | fn | saveSelectedItems | (private) |
| 559 | fn | loadSelectedItems | (private) |
| 567 | fn | addItem | (internal) |
| 581 | fn | removeItem | (internal) |
| 587 | fn | isSelected | (internal) |
| 592 | fn | toggleItem | (internal) |
| 602 | fn | pruneInvalidItems | (internal) |
| 606 | fn | autoSelectNewAccounts | (internal) |
| 621 | fn | enforceMaxItems | (private) |
| 628 | fn | clampedMenuBarMax | (private) |

## Quotio/Models/Models.swift (640 lines)

| Line | Kind | Name | Visibility |
| ---- | ---- | ---- | ---------- |
| 336 | fn | hash | (internal) |
| 527 | method | init | (internal) |
| 544 | mod | extension Int | (internal) |
| 590 | fn | validate | (internal) |
| 630 | fn | sanitize | (internal) |

