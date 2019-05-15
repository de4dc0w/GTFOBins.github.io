---
functions:
  file-read:
    - description: Read file by make file STDIN redirection
      code: |
        echo "$(<file_to_read)"
---
