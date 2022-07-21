---
created: 2022-07-21T13:53:01-06:00
updated: 2022-07-21T14:03:01-06:00
---


## PreReqs


1. [ ] [[Insomnia]]
2. [ ] [[obsidian-mkdocs]]



## Steps


### Step ?: `Copy as cURL (bash)`
- *Never ever windows. Try comparing both. Insomnia Request Import is cool with Bash version, which makes sense, but not the Windows version.*


#### #Challenge to Fix Insomnia
#todo
- Insomnia is Open Source by Kong.
- Main reason I chose it.
- WE COULD FIX THIS!


- [ ] Takers? Post Insomnia Pull Request or Working GitHub Links 

- [ ] Form the CFOSC (ColdFusion Open Source Consortium) to review
	- *get it... the CFosCs? CFC, #haha *
	- Chat with Mark to chat with Adobe once proposal/presentation is ready. Noooooooo, it's a Consortium, we will just start it, gain traction, see if Adorbs wants in.

- [ ] 




#screenshot

![[Edge Developer Tools - HOWTO Copy Requests to Insomnia REST Client-pasted-20220721134721802.png]]






## 
cmd

### `Copy as cURL (bash)` #UseThis
```bash
curl 'https://jobindj.github.io/obsidian-publish-mkdocs/search/search_index.json' \
  -H 'authority: jobindj.github.io' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9' \
  -H 'cache-control: no-cache' \
  -H 'dnt: 1' \
  -H 'pragma: no-cache' \
  -H 'referer: https://jobindj.github.io/obsidian-publish-mkdocs/Features/Text%20Formatting/' \
  -H 'sec-ch-ua: " Not;A Brand";v="99", "Microsoft Edge";v="103", "Chromium";v="103"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.5060.114 Safari/537.36 Edg/103.0.1264.62' \
  --compressed
```


### `Copy as cURL (cmd)` #DontUseThis

```powershell
curl "https://jobindj.github.io/obsidian-publish-mkdocs/search/search_index.json" ^
  -H "authority: jobindj.github.io" ^
  -H "accept: */*" ^
  -H "accept-language: en-US,en;q=0.9" ^
  -H "cache-control: no-cache" ^
  -H "dnt: 1" ^
  -H "pragma: no-cache" ^
  -H "referer: https://jobindj.github.io/obsidian-publish-mkdocs/Features/Text^%^20Formatting/" ^
  -H "sec-ch-ua: ^\^" Not;A Brand^\^";v=^\^"99^\^", ^\^"Microsoft Edge^\^";v=^\^"103^\^", ^\^"Chromium^\^";v=^\^"103^\^"" ^
  -H "sec-ch-ua-mobile: ?0" ^
  -H "sec-ch-ua-platform: ^\^"Windows^\^"" ^
  -H "sec-fetch-dest: empty" ^
  -H "sec-fetch-mode: cors" ^
  -H "sec-fetch-site: same-origin" ^
  -H "user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.5060.114 Safari/537.36 Edg/103.0.1264.62" ^
  --compressed
```





curl 'https://jobindj.github.io/obsidian-publish-mkdocs/search/search_index.json' \
  -H 'authority: jobindj.github.io' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9' \
  -H 'cache-control: no-cache' \
  -H 'dnt: 1' \
  -H 'pragma: no-cache' \
  -H 'referer: https://jobindj.github.io/obsidian-publish-mkdocs/Features/Text%20Formatting/' \
  -H 'sec-ch-ua: " Not;A Brand";v="99", "Microsoft Edge";v="103", "Chromium";v="103"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.5060.114 Safari/537.36 Edg/103.0.1264.62' \
  --compressed



curl "https://jobindj.github.io/obsidian-publish-mkdocs/search/search_index.json" ^
  -H "authority: jobindj.github.io" ^
  -H "accept: */*" ^
  -H "accept-language: en-US,en;q=0.9" ^
  -H "cache-control: no-cache" ^
  -H "dnt: 1" ^
  -H "pragma: no-cache" ^
  -H "referer: https://jobindj.github.io/obsidian-publish-mkdocs/Features/Text^%^20Formatting/" ^
  -H "sec-ch-ua: ^\^" Not;A Brand^\^";v=^\^"99^\^", ^\^"Microsoft Edge^\^";v=^\^"103^\^", ^\^"Chromium^\^";v=^\^"103^\^"" ^
  -H "sec-ch-ua-mobile: ?0" ^
  -H "sec-ch-ua-platform: ^\^"Windows^\^"" ^
  -H "sec-fetch-dest: empty" ^
  -H "sec-fetch-mode: cors" ^
  -H "sec-fetch-site: same-origin" ^
  -H "user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.5060.114 Safari/537.36 Edg/103.0.1264.62" ^
  --compressed


$session = New-Object Microsoft.PowerShell.Commands.WebRequestSession
$session.UserAgent = "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/103.0.5060.114 Safari/537.36 Edg/103.0.1264.62"
Invoke-WebRequest -UseBasicParsing -Uri "https://jobindj.github.io/obsidian-publish-mkdocs/search/search_index.json" `
-WebSession $session `
-Headers @{
"authority"="jobindj.github.io"
  "method"="GET"
  "path"="/obsidian-publish-mkdocs/search/search_index.json"
  "scheme"="https"
  "accept"="*/*"
  "accept-encoding"="gzip, deflate, br"
  "accept-language"="en-US,en;q=0.9"
  "cache-control"="no-cache"
  "dnt"="1"
  "pragma"="no-cache"
  "referer"="https://jobindj.github.io/obsidian-publish-mkdocs/Features/Text%20Formatting/"
  "sec-ch-ua"="`" Not;A Brand`";v=`"99`", `"Microsoft Edge`";v=`"103`", `"Chromium`";v=`"103`""
  "sec-ch-ua-mobile"="?0"
  "sec-ch-ua-platform"="`"Windows`""
  "sec-fetch-dest"="empty"
  "sec-fetch-mode"="cors"
  "sec-fetch-site"="same-origin"
}





fetch("https://jobindj.github.io/obsidian-publish-mkdocs/search/search_index.json", {
  "headers": {
    "accept": "*/*",
    "accept-language": "en-US,en;q=0.9",
    "cache-control": "no-cache",
    "pragma": "no-cache",
    "sec-ch-ua": "\" Not;A Brand\";v=\"99\", \"Microsoft Edge\";v=\"103\", \"Chromium\";v=\"103\"",
    "sec-ch-ua-mobile": "?0",
    "sec-ch-ua-platform": "\"Windows\"",
    "sec-fetch-dest": "empty",
    "sec-fetch-mode": "cors",
    "sec-fetch-site": "same-origin"
  },
  "referrer": "https://jobindj.github.io/obsidian-publish-mkdocs/Features/Text%20Formatting/",
  "referrerPolicy": "strict-origin-when-cross-origin",
  "body": null,
  "method": "GET",
  "mode": "cors",
  "credentials": "omit"
});


![[Edge Developer Tools - HOWTO Copy Requests to Insomnia REST Client-pasted-20220721140230352.png]]





