# PanJS
PanDownload Web, built with CloudFlare Workers (based on [TkzcM/baiduwp](https://github.com/TkzcM/baiduwp))
# Demo
[PanJS](https://pjs.jshir.com)
# Usage
Getting access to the shared files:
```
headers:{
    'user-agent': 'Some UA',
    'Cookie': 'BDUSS=INPUT YOUR BDUSS HERE; STOKEN=INPUT YOUR STOKEN HERE'
  }
```
Verifying your qualification of downloading to avoid abuse
```
async function verifyidk(idk){
	const pdk = "**INPUT THE KEY THAT YOU SET HERE**"
	if(idk == pdk){
        return 0
      }
      else {
        return 1
      }  
  }
```
# Thanks
[baiduwp](https://github.com/TkzcM/baiduwp): basic codes

[PanDownload](https://pandownload.com): static pages

[KinhDown](https://t.me/kinhdown): client type

[PNL](https://www.lanzous.com/u/pnl): download method

[acgotaku/BaiduExporter](https://github.com/acgotaku/BaiduExporter): send to aria2
