# 課題
FizzBuzz

# 環境構築
rubyのバージョンは`.ruby-version`を確認してください

```
$ bundle install
```

# 完了条件
## テストが通ること
```
$ ruby test/fizz_buzz_test.rb
Run options: --seed 20119

# Running:

.

Finished in 0.000841s, 1189.0606 runs/s, 9512.4851 assertions/s.
1 runs, 8 assertions, 0 failures, 0 errors, 0 skips
```

## Lintが通ること
```
$ bundle exec rubocop
Inspecting 1 file
.

1 file inspected, no offenses detected
```
