Goals for this project and how this will perform.
======

What to backup?
------

* Dump wallet labels/public keys/private keys of all grc addresses in the wallet.
* Export it to a user friendly file for printing of paper backup of wallet.

Things to consider?
------

* Wallet must be fully unlocked for private keys to be dumped. We must verify this.
* User must understand that this information should be printed or stored and immediatly deleted as this information can be used to compromise the wallet even without wallet.dat!
* This will backup the keys of hidden change wallets that you would normally see in coin control when there is balance in the addresses.

End goal?
------

* Have another hard copy way to backup wallet with the important keys that can be used to recover the wallet if they were to lose all copies of backups related to wallet.dat
* Automated process to simplify the process.
