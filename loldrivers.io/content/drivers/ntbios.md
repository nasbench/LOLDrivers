+++

description = ""
title = "ntbios.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}




# ntbios.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}




### Description


Driver used in the Daxin malware campaign.


- **Created**: 2023-02-28
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

| Use Case | Privilages | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

```
sc.exe create ntbios.sys binPath=C:\windows\temp\ntbios.sys type=kernel
sc.exe start ntbios.sys
```

### Resources
<br>


<li><a href="https://gist.github.com/MHaggis/9ab3bb795a6018d70fb11fa7c31f8f48">https://gist.github.com/MHaggis/9ab3bb795a6018d70fb11fa7c31f8f48</a></li>

<li><a href="https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/daxin-backdoor-espionage">https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/daxin-backdoor-espionage</a></li>


<br>


##### Known Vulnerable Samples

| Filename: ntbios.sys |
|:---- |
|MD5: <a href="https://www.virustotal.com/gui/file/{&#39;Filename&#39;: &#39;ntbios.sys&#39;, &#39;MD5&#39;: &#39;&#39;, &#39;SHA1&#39;: &#39;&#39;, &#39;SHA256&#39;: &#39;96bf3ee7c6673b69c6aa173bb44e21fa636b1c2c73f4356a7599c121284a51cc&#39;}"></a>|
|SHA1: <a href="https://www.virustotal.com/gui/file/{&#39;Filename&#39;: &#39;ntbios.sys&#39;, &#39;MD5&#39;: &#39;&#39;, &#39;SHA1&#39;: &#39;&#39;, &#39;SHA256&#39;: &#39;96bf3ee7c6673b69c6aa173bb44e21fa636b1c2c73f4356a7599c121284a51cc&#39;}"></a>|
|SHA256: <a href="https://www.virustotal.com/gui/file/{&#39;Filename&#39;: &#39;ntbios.sys&#39;, &#39;MD5&#39;: &#39;&#39;, &#39;SHA1&#39;: &#39;&#39;, &#39;SHA256&#39;: &#39;96bf3ee7c6673b69c6aa173bb44e21fa636b1c2c73f4356a7599c121284a51cc&#39;}">96bf3ee7c6673b69c6aa173bb44e21fa636b1c2c73f4356a7599c121284a51cc</a>|




### Binary Metadata
<br>

- binary: 
- Verified: Unsigned
- Date: 10:26 AM 11/19/2009
- Publisher: n/a
- Company: Microsoft Corporation
- Description: ntbios driver
- Product:  Microsoft(R) Windows (R) NT Operating System
- ProductVersion: 
- FileVersion: 
- MachineType: 
- OriginalFilename: 

[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/ntbios.sys.yml)

*last_updated:* 2023-03-10


{{< /column >}}
{{< /block >}}