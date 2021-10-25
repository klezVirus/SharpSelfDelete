# SharpSelfDelete
C# implementation of the research by @jonaslyk and the drafted PoC from @LloydLabs

## Why?
Well, for fun I guess, and to add another module for [Inceptor](https://github.com/klezVirus/inceptor).

## How do I run this?
1. Clone the project
2. Load the .csproj in VS2019 or similar
3. Build the project
4. Run the SharpSelfDelete.exe

## Ok, How do I use it, for real?
Well, I guess the best way to use it is to take the code, and adapt it to an existing implant. There is no recommended way to do it, as long as it works.

## Thanks

Huge thanks to [_EthicalChaos_](https://twitter.com/_EthicalChaos_) for helping me out with a Marshalling issue.

## Credit

The original research was done by [Jonas Lyk](https://twitter.com/jonasLyk), the screenshot showing the technique can be found [here](https://pbs.twimg.com/media/Er2W8NFXIAAWZ5a?format=png&name=4096x4096)

The first PoC in C was created by [@LloydLabs](https://twitter.com/LloydLabs/): [delete-self-poc](https://github.com/LloydLabs/delete-self-poc)

A while ago, Espresso Cake created a BOF version, available at [Self_deletion_BOF](https://github.com/EspressoCake/Self_Deletion_BOF).

## Any known downsides?
- This is just a PoC using P/Invoke, so the known downsides are the same of any implant using P/Invoke to invoke Windows APIs. 
