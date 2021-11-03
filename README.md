# GORM Sqlite Driver (pure go)

Based on [gorm.io/driver/sqlite](https://github.com/go-gorm/sqlite) 
and [modernc.org/sqlite](https://gitlab.com/cznic/sqlite)

## USAGE

```go
import (
  "github.com/bboehmke/gorm-sqlite"
  "gorm.io/gorm"
)

// modernc.org/sqlite
db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.
