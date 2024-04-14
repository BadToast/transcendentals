# transcendentals
Diagrams using Mermaid in Markdown

## Greek Philosophy
```mermaid
block-beta
block:Greek
  columns 3
  space being space
  space:3
  one good true
  one --> being
  true --> being
  good --"property of"--> being
end
```

## Aquinas's 6 Transcendentals
```mermaid
block-beta
block:Aquinas
columns 5
  space:2
  b["being 
  (ens)"]
  space:2

  space:5

  r["thing 
  (res)"]
  o["one 
  (unum)"]
  a["otherness 
  (aliquid)"]
  t["true 
  (verum)"]
  g["good 
  (bonum)"]
  r --> b
  o --> b 
  t --> b 
  g --> b 
  a --"property of"--> b
end
```

## Aquinas's Ordo of the 4 Transcendentals
```mermaid
block-beta
block:Aquinas2
columns 14
  b2["being"]
  space:3
  o2["one"]
  space:3
  t2["true"]
  space:3
  g2["good"]
  o2 --"presupposes"--> b2
  t2 --"presupposes"--> o2 
  g2 --"presupposes"--> t2
end
```

## Kovach's Attempted Addition of Beauty
```mermaid
block-beta
block:Aquinas2
columns 13
  b2["being"]
  space:3
  o2["one"]
  space:3
  t2["true"]
  space:3
  g2["good"]
  space:13
  space:6
  b["beauty"]
  space:6
  o2 -."presupposes?".-> b2
  t2 -."presupposes?".-> o2 
  g2 -."presupposes?".-> t2
  b --"synthesizes"--> b2
  b --"synthesizes"--> o2
  b --"synthesizes"--> t2
  b --"synthesizes"--> g2
end
```

## Czapiewski's Attempted Addition of Beauty
```mermaid
block-beta
block:Aquinas2
columns 13
  space:11
  t2["true"]
  space

  space:13

  b2["being"]
  space:3
  o2["one"]
  space:3
  b["beauty"]
  space:4

  space:13

  space:11
  g2["good"]
  space
  o2 -."presupposes?".-> b2
  t2 -."presupposes?".-> o2 
  g2 -."presupposes?".-> t2
  b -."presupposes?".-> o2

  b --"union of"--> t2
  b --"union of"--> g2
end
```

## Aquinas on Beauty, True, Good and the 4 Causes
```mermaid
block-beta
block:Aquinas2
columns 5
  mc["material cause"]
  fc["formal cause"]
  Fc["final cause"]:2
  ec["efficient cause"]

  space:5

  space:1
  b["beauty"]
  t["true"]
  g["good"]
  space:1

  b--"example of"-->fc
  t--"example of"-->Fc
  g--"example of"-->Fc
end
```

## Greek's View on Good & Beauty
```mermaid
block-beta
block:Aquinas2
columns 4
  g["good"]
  space:2
  b["beauty"]
  b-->g
  g--"is"-->b
end
```

## Aertsen on Aquinas's View of True, Good, & Beautiful
```mermaid
block-beta
block:Aquinas2
columns 8
  space
  c["cognition"]
  space:2
  a["appetite"]
  space:3

  space:8

  space
  t["true"]
  space:2
  g["good"]
  space:2
  b["beauty"]

  space:8

  space
  i["intellect"]
  space:2
  w["will"]
  space:2

  t--"included in"-->g
  g--"is"-->b
  t--"formal object of"-->i
  g--"formal object of"-->w
  g--"power of"-->a
  t--"power of"-->c
end
```
