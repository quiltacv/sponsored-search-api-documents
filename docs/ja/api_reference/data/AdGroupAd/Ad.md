# Ad
Adオブジェクトは、広告に関する情報を表します。

### Service
+ [AdGroupAdService](../../services/AdGroupAdService.md)

### Namespace
[AdGroupAdService#Namespace](../../services/AdGroupAdService.md#namespace)

<table>
 <tr>
  <th>Field</th>
  <th>Type</th>
  <th>Description</th>
  <th>response</th>
  <th>get</th>
  <th>add</th>
  <th>set</th>
  <th>remove</th>
 </tr>
  <tr>
  <td>type</td>
  <td>enum <a href="AdType.md">AdType</a></td>
  <td>広告の種類です。</td>
  <td>yes</td>
  <td>-</td>
  <td>Requirement</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>advancedUrl</td>
  <td>xsd:string</td>
  <td>最終リンク先URLです。</td>
  <td>yes</td>
  <td>-</td>
  <td>Optional<br>※adTypeがDYNAMIC_SEARCH_LINKED_ADの場合:Ignore。</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>additionalAdvancedUrls[0..9]</td>
  <td><a href="AdGroupAdAdditionalAdvancedUrls.md">AdGroupAdAdditionalAdvancedUrls</a></td>
  <td>最終リンク先URLです。<br>2件目以降の最終リンク先URLを設定します。</td>
  <td>yes</td>
  <td>-</td>
  <td>Optional<br>※adTypeがDYNAMIC_SEARCH_LINKED_ADの場合:Ignore。</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>advancedMobileUrl</td>
  <td>xsd:string</td>
  <td>最終リンク先URL（スマート フォン）です。</td>
  <td>yes</td>
  <td>-</td>
  <td>Optional<br>※adTypeがDYNAMIC_SEARCH_LINKED_ADの場合:Ignore。</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>additionalAdvancedMobileUrls[0..9]</td>
  <td><a href="AdGroupAdAdditionalAdvancedMobileUrls.md">AdGroupAdAdditionalAdvancedMobileUrls</a></td>
  <td>最終リンク先URL（スマート フォン）です。<br>2件目以降の最終リンク先URL（スマート フォン）<br>を設定します。</td>
  <td>yes</td>
  <td>-</td>
  <td>Optional<br>※adTypeがDYNAMIC_SEARCH_LINKED_ADの場合:Ignore。</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>trackingUrl</td>
  <td>xsd:string</td>
  <td>トラッキングURLです。</td>
  <td>yes</td>
  <td>-</td>
  <td>Optional</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>customParameters</td>
  <td><a href="CustomParameters.md">CustomParameters</a></td>
  <td>カスタムパラメータです。</td>
  <td>yes</td>
  <td>-</td>
  <td>Optional</td>
  <td>-</td>
  <td>-</td>
 </tr>

<tr>
  <td>url</td>
  <td>xsd:string</td>
  <td>移行前のリンク先URLです。</td>
  <td>yes</td>
  <td>-</td>
  <td>Ignore</td>
  <td>Ignore</td>
  <td>Ignore</td>
 </tr>
 <tr>
  <td>displayUrl</td>
  <td>xsd:string</td>
  <td>表示URLです。</td>
  <td>yes</td>
  <td>-</td>
  <td>Ignore</td>
  <td>Ignore</td>
  <td>Ignore</td>
 </tr>
 <tr>
  <td>headline</td>
  <td>xsd:string</td>
  <td>タイトル文です。</td>
  <td>yes</td>
  <td>-</td>
  <td>Requirement<br>※adTypeがDYNAMIC_SEARCH_LINKED_ADの場合:Ignore。</td>
  <td>Ignore</td>
  <td>Ignore</td>
 </tr>
 <tr>
  <td>description</td>
  <td>xsd:string</td>
  <td>説明文です。</td>
  <td>yes</td>
  <td>-</td>
  <td>Requirement</td>
  <td>Ignore</td>
  <td>Ignore</td>
 </tr>
 <tr>
  <td>devicePreference</td>
  <td>enum <a href="DevicePreference.md">DevicePreference</a></td>
  <td>優先デバイスです。<br>※スマートフォンに優先的に配信します。</td>
  <td>yes</td>
  <td>-</td>
  <td>Optional<br>※DOUBLE_TEXT_ADの場合、Ignore。</td>
  <td>Ignore</td>
  <td>Ignore</td>
 </tr>
</table>

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>
