| クラス                   | vCPU         | RAM   |
| --------------------- | ------------ | ----- |
| medium                | 4 @ 2.7 GHz  | 8 GB  |
| macos.x86.medium.gen2 | 4 @ 3.2 GHz  | 8 GB  |
| large                 | 8 @ 2.7 GHz  | 16 GB |
| macos.m1.medium.gen1  | 4 @ 3.2 GHz  | 6GB   |
| macos.m1.large.gen1   | 8 @ 3.2 GHz  | 12GB  |
| macos.x86.metal.gen1  | 12 @ 3.2 GHz | 32 GB |
{: class="table table-striped"}

WARNING: `medium` および `large` リソースクラスは、2023年10月2日に非推奨になります。 Xcode v14.2は、macOSリソースでサポートされる最新バージョンです。 詳しくは https://discuss.circleci.com/t/m1-medium-m1-large/48290[お知らせ]をご覧ください。

[NOTE]
====
`macos.x86.metal.gen1` リソースは、最低 24 時間の利用が必要です。 このリソースクラスの詳細については、link:https://circleci.com/docs/ja/dedicated-hosts-macos/[macOS の専有ホスト]を参照して下さい。

`large` リソースクラスは、年間契約のお客様のみご利用いただけます。 年間契約プランの詳細については、link:https://support.circleci.com/hc/ja/requests/new[サポートチケット]をオープンしお問い合わせください。 
====
