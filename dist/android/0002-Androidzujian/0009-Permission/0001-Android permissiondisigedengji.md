java代码：
```  
android:protectionLevel="normal"
android:protectionLevel="dangerous"
android:protectionLevel="signature"
android:protectionLevel="signatureOrSystem"
```
#### normal
默认值。一个事实给请求应用访问许可中分离出应用特点出发，以最小的风险其他的应用，系统或用户。系统自动奖助金这种类型的许可，在安装一个请求的应用程序，而不要求给予用户的明确的批准(尽管用户总是选择安装前审查这些权限)。
#### dangerous
一个高风险许可，这将会给一个请求的应用程序访问私人用户数据或控制的设备，可以负面影响的用户。因为这种类型的许可介绍一个潜在的危险，系统可能并不会自动给你的请求的应用程序。例如,任何危险的权限要求，一项应用也许被显示在用户和需要确认在进行下一步之前，或其他方法可能要采取防止用户自动允许使用这些设备。
#### signature
一个权限，该系统奖助金，只有在请求的应用程序是相同的证书签署的申请许可声明。如果匹配，系统自动证书发给许可未通知用户或用户的明确要求批准。
#### signatureOrSystem
一个权限，该系统应用程序的奖助金只有在机器人系统的形象，或者是用同样的证书签署和其它系统的形象。这个选项,请避免使用“签名”应该足以保护水平为最需要的作品无论在哪申请安装。“signatureOrSystem“许可用于某些特殊情况下，应用多供应商建立一个系统的形象和需要分享的具体特征明确，因为他们同被建造。