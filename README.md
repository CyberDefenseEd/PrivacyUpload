# PrivacyUpload

PrivacyUpload is a free, open-source, privacy-focused file uploader. This small, self-hostable solution is designed to help prevent the tracking commonly done by mainstream upload services such as Mega.nz, MediaFire, and others.

## Why PrivacyUpload?

Many popular file-sharing services are known to track user activity, collect data, and sometimes even share that data with third parties. PrivacyUpload offers a simple alternative, allowing you to share files securely and privately.

## Key Benefits

- **Privacy-Focused:** Unlike traditional file uploaders, PrivacyUpload prioritizes user privacy by ensuring no tracking or data collection.
- **Open-Source:** Fully open-source, allowing you to inspect, modify, and contribute to the code.
- **Self-Hostable:** Easily deploy on your own server to have complete control over your files and data.

## Additional Features
- **Speed:** No speed limits. Keep the fastest upload speeds your server can provide.
- **Chunk Uploading:** Upload files in smaller chunks, avoiding the need to load the entire file into memory at once, unlike traditional uploaders.

## Getting Started
```sh
git clone https://github.com/CyberDefenseEd/PrivacyUpload
```
### Run your server
Install dependencies 
```
cd PrivacyUpload
go build
```
#### Production
```sh
./PrivacyUpload
```

## License
```
MIT License

Copyright (c) 2024 Illicit

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
