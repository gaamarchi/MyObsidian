---
cssclasses:
  - dashboard
---
# Study
- Topics of the week
	- [[note1]]
- Technical readings
- 
# Personal
- Projects 
- Readings
- Daily's Note
`$=dv.list(dv.pages('"Journal/daily"').limit(7).file.link)`
# Vault 
- Info
	- Zettelkasten -> `$=dv.pages('"Zettelkasten"').length - dv.pages('"Zettelkasten/MOC"').length`
		- Permanent Notes -> `$=dv.pages('"Zettelkasten"').length - dv.pages('"Zettelkasten/MOC"').length -dv.pages('"Zettelkasten/inbox"').length `
	- Attachments -> `$=dv.pages('"Resources/Attachments"').length`
	- Archive -> `$=dv.pages('"Resources/Archive"').length`
	-  Canvas-> `$=dv.pages('"Canvas"').length`
- Your templates (`$=dv.pages('"Resources/Template"').length`)
	`$=dv.list(dv.pages('"Resources/Template"').file.link)`
- Recent Files
`$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(5).file.link)`
- MOCs(`$=dv.pages('"Zettelkasten/MOC"').length`)
`$=dv.list(dv.pages('"Zettelkasten/MOC"').file.link)`