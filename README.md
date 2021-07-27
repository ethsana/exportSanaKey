# exportSanaKey

`exportSanaKey` is a command-line utility to get the Ethereum keys from your Sana keystore file. 

We reccomend the usage of `ant-clef`, but if you inadvertedly started `ant` without `ant-clef`, this is as good as it gets.

## Requirements
- [golang](https://golang.org/doc/install)
- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## HowTo
- Clone this repo and navigate to directory
- run `go run main.go \<sourceDirContainingSanaKeys\> \<password\>`
- Make a backup of your key in a safe place
- Import your keys in a trusted Ethereum wallet (such as Metamask)
- Validate if the address inside your wallet corresponds with the Ethereum address of your Sana node (`localhost:1635/addresses`)

With gratitude to @jmozah <3

## Warning
Never interact with your chequebook directly, but always do so via `ant` APIs. If you would call into functions of your chequebook with your imported key in Metamask, you might screw things up for Sana.
