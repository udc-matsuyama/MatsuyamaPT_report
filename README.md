## PDFファイル
PDFは[Releases](https://github.com/udc-matsuyama/MatsuyamaPT_report/releases)からダウンロードしてください。

## How to Push and Release on GitHub

An Example

```bash
# Push
git add .
git commit -m "your commit message"
git push origin origin-branch-name

# Make Release
git tag -a vX.X.X -m "your tag message"
git push origin vX.X.X
```