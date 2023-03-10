+++

description = ""
title = "Sense5Ext.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}




# Sense5Ext.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}




### Description


Driver categorized as POORTRY by Mandiant.


- **Created**: 2023-03-04
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

| Use Case | Privilages | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

```
sc.exe create Sense5Ext.sys binPath=C:\windows\temp\Sense5Ext.sys type=kernel
sc.exe start Sense5Ext.sys
```

### Resources
<br>


<li><a href="https://www.mandiant.com/resources/blog/hunting-attestation-signed-malware">https://www.mandiant.com/resources/blog/hunting-attestation-signed-malware</a></li>


<br>


##### Known Vulnerable Samples

| Filename: Sense5Ext.sys |
|:---- |
|MD5: <a href="https://www.virustotal.com/gui/file/{&#39;Filename&#39;: &#39;Sense5Ext.sys&#39;, &#39;MD5&#39;: &#39;&#39;, &#39;SHA1&#39;: &#39;&#39;, &#39;SHA256&#39;: &#39;f9844524fb0009e5b784c21c7bad4220&#39;}"></a>|
|SHA1: <a href="https://www.virustotal.com/gui/file/{&#39;Filename&#39;: &#39;Sense5Ext.sys&#39;, &#39;MD5&#39;: &#39;&#39;, &#39;SHA1&#39;: &#39;&#39;, &#39;SHA256&#39;: &#39;f9844524fb0009e5b784c21c7bad4220&#39;}"></a>|
|SHA256: <a href="https://www.virustotal.com/gui/file/{&#39;Filename&#39;: &#39;Sense5Ext.sys&#39;, &#39;MD5&#39;: &#39;&#39;, &#39;SHA1&#39;: &#39;&#39;, &#39;SHA256&#39;: &#39;f9844524fb0009e5b784c21c7bad4220&#39;}">f9844524fb0009e5b784c21c7bad4220</a>|




### Binary Metadata
<br>

- binary: 
- Verified: 
- Date: 
- Publisher: 
- Company: 
- Description: 
- Product: 
- ProductVersion: 
- FileVersion: 
- MachineType: 
- OriginalFilename: 

[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/sense5ext.sys.yml)

*last_updated:* 2023-03-10


{{< /column >}}
{{< /block >}}