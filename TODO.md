# TODO
-----

- [x] Switch control master to regular/non-pty cmd
- [ ] Try password auth on controlMaster
- [ ] Try sudo with password
- [x] Change control path to use ssh's templating. Append session/targetid
- [ ] Create default socket dir
  - In `.ssh` something like `~/.ssh/bevy/`
  - or maybe...  `~/.cache`
- [x] Handle system logging at all. Logrus/golog
