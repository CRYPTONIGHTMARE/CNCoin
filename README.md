# CNCoin v0.0.2 CLI

## QuickStart (Releases Binary)

0. Download and Extract Archive (cncoin-linux.tar.gz)
1. Run `./cncoind` and wait for the `blockchain` to be synchronised. This
should take some time.
2. Run `./simplewallet` after the message `SYNCHRONIZED OK` appears in `cncoind` output.
3. Generate a wallet.
4. ?

## Running on Common Cryptonote Binaries (Windows Advanced)

Unfortunately official `MacOS` binaries are outdated but `Windows` users could try – CNC if fully reverse compatible with `Cryptonote` code base right now.

0. Download and extract archive from `Forknote` Releases Page https://github.com/forknote/forknote/releases latest version of binaries.
1. Download and put in `configs` folder file `cncoin.conf` from this repo.
2. Run `./forknoted --config-file configs/cncoin.conf`. If You see message about wrong block format or block validation erros – bad luck, binaries are outdated.
3. Run `./simplewallet --config-file configs/cncoin.conf` after the message `SYNCHRONIZED OK` appears in `cncoind` output.
4. Generate a wallet.
5. ?
