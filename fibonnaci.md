What does this code?
```ruby
def fibs(num)
  return arr[0...num] if num <= 2
  
  ary = [0, 1]
  (3..num).each { |i| ary << (ary[i - 3] + ary[i - 2])}
  ary
end
p fibs(3)
```

