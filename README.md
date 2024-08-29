# AppDomainManager-Injection-CSharp
This repository has all components necessary for AppDomainManager injection. This technique can be utilized to use any Microsoft.NET application as LOLBIN. <br/>
1. Copy app.config to your target Microsoft.NET application location.<br/>
2. Edit necessary entries in app.config (name, publicKeyToken, href).<br/>
3. Rename app.config to target_binary.exe.config.<br/>
4. Host DLL for injection.<br/>
5. Execute target_binary.exe<br/>
