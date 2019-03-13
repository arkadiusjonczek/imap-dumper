# imapdump

Backup and restore your imap mailboxes.

## Installation

```bash
clone https://github.com/arkadiusjonczek/imapdump.git
cd imapdump
composer install
chmod u+x imap
./imap
```

## Usage

Info about your mailbox usage and limit quota:

```bash
php imap info <host> <username>
```

List all your mailboxes with number of messages:

```bash
php imap ls <host> <username>
```

Backup your mailboxes:

```bash
php imap backup <host> <username> <filepath>
```