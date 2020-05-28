# 中州韻粵語分歧拼音系統排版工具

**℞**: `tanxpyox/rime-cantonese-schemes-editor`

依賴於: [`rime-cantonese`](https://github.com/rime/rime-cantonese)

## 說明

* 呢個程式庫嘅schema係用嚟輸入「耶魯」、「教院」、「黃錫凌」、「劉錫祥」等嘅分歧拼音系統嘅工具。
* 只要啓用呢個程式庫入面嘅schema，**輸入正確嘅[粵拼](https://www.lshk.org/jyutping)**，選字框上面就會顯示正確嘅分歧拼音嘞。(用<kbd>Ctrl</kbd> + <kbd> Enter </kbd>就可以將選字框入面嘅字打出嚟）
* 目前支援以下嘅方案

 方案名| 檔名 | 「春眠不覺曉」
-----|------| ------
[粵拼（跟機）](https://github.com/rime/rime-cantonese)| `jyut6ping3.schema.yaml` | ceon¹ min⁴ bat¹ gok³ hiu²
[IPA（跟機）](https://github.com/rime/rime-cantonese)| `jyut6ping3_ipa.schema.yaml` | t͡sʰɵn˥ miːn˨˩ pɐt̚˥ kɔːk̚˧ hiːu˧˥
耶魯（舊版）| `jyut6ping3_yale.schema.yaml` | chēun mìhn bāt gok híu
耶魯（新版）| `jyut6ping3_yale_new.schema.yaml`|  cheun¹ min⁴ bat¹ gok³ hiu²
教院| `jyut6ping3_edu.schema.yaml` |  tsoen¹ min⁴ bat⁷ gok⁸ hiu²
黃錫凌| `jyut6ping3_wong.schema.yaml` |  ˈtseun ˌmin ˈbat ˉgok ˊhiu
劉錫祥| `jyut6ping3_lau.schema.yaml` | cheun¹ min⁴ bat¹ gok³ hiu²
饒秉才| `jyut6ping3_rao.schema.yaml` | cên¹ min⁴ bed¹ gog³ hiu²
Meyer-Wempe| `jyut6ping3_mw.schema.yaml` | ts'un mîn pat kòk híu
[注音（國民政府）](https://github.com/tanxpyox/rime-cantonese-bpmf)| `jyut6ping3_bpmf_ng.schema.yaml` |ㄘ￥ㄣˉ ㄇㄧㄣˊ ㄅㆿㆵ˙ ㄍㄛㆶ ㄏㄧㄨˇ
[注音（人民政府）](https://github.com/tanxpyox/rime-cantonese-bpmf)| `jyut6ping3_bpmf_cpg.schema.yaml` |ㄑㆾㄋˉ ㄇㄧㄋˊ ㄅㆿㆵ˙ ㄍㄛㆻ ㄏㄧㄨˇ
