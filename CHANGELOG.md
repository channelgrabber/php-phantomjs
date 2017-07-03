# Changelog

## 3.1.8 - 03/07/2017
### [CGIV-8595](https://orderhub.atlassian.net/browse/CGIV-8595)
- Updated upstream version to the latest 3.x release (3.1.5)
- Switched from using `proc_open` to using Symfony Process as pipes were blocking.

## 3.1.7 - 20/11/2014
### [CGIV-4172](https://channelgrabber.atlassian.net/browse/CGIV-4172)
Added so that phantomJS will always have the option telling it to
accept all SSL options

## 3.1.6 - 14/11/2014
### [CGIV-4103](https://channelgrabber.atlassian.net/browse/CGIV-4103)
Increased request timeout to 30000 (30 seconds) rather than the previous
5000 (5 seconds). This was so that local VMs were timing out far too
often

## 3.1.5 - 23/10/2014
### [CGIV-3688](https://channelgrabber.atlassian.net/browse/CGIV-3688)
Added downloadLocation and downloadContentType fields.
Added the ability to download files using content-disposition headers
