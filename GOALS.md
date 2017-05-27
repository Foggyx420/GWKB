Goals for this project and how this will perform.
======

What to backup?
------

* Find the account associated with the users gridcoin wallet.
* Dump the public/private key of the account of the gridcoin users wallet.
* Find the main GRC address associated directly with the account address.
* Dump wallet labels/public keys/private keys of all grc addresses on the account.
* Export it to a user friendly file for printing of paper backup of wallet.

Things to consider?
------

* Wallet must be fully unlocked for private keys to be dumped. We must verify this.
* If we pull the account address then that information will displayed in receive coins section. This being the case the user must understand before hand why a address appeared. The user must also understand what an account address is!
* User must understand that this information should be printed or stored and immediatly deleted as this information can be used to compromise the wallet even without wallet.dat!

End goal?
------

* Have another hard copy way to backup wallet with the important keys that can be used to recover the wallet if they were to lose all copies of backups related to wallet.dat
* Automated process to simplify the process.
