# ansible-homebrew-cask

Install Homebrew Cask via Homebrew. Does nothing on non-macOS platforms.

## Dependencies

* [icopp.homebrew](https://github.com/icopp/ansible-homebrew) (included as repository dependency)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.homebrew-cask
```

## License

MIT
