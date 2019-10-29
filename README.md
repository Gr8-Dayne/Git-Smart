# Git-Smart

### Version Control
- Allows tracking of modifications and the User responsible
- Enables reverting a file/project to a previous version
- Allows users to compare current and previous versions of file/project
- Assists in the rectification of mistakes

#### Local Version Control
- Stored on your hard drive to track changes locally

#### Centralized Version Control
- Stored on a *single server* and can be accessed by multiple users

#### Distributed Version Control
- Allows users to create mirrored repositories

## Git
- A Distributed Version Control (DVCS) that stores data in a file system using snapshots
- File/project history resides on local disks
- Can detect corruption
- Tracks all changes

#### Three main states:
- Committed - data is stored locally
- Modified - file has been changed but not committed
- Staged - flagged a file`s changed version to be committed (updated) in the next snapshot

#### Customization
1. Identity
   - `git config --global user.name "Jane Smith"`
   - `git config --global user.email "example@email.com"`
2. Check settings
   - `git config --list`
3. Help
   - `git help command`
   - `git command --help`
   - `man git-command`

