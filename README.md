# DOG(1)

## NAME

dog - opposite of cat

## SYNOPSIS

```
dog [-c algorithm] [-e algorithm] [-d algorithm] [-h algorithm] [-i from:to] [-l] [...]
```

## DESCRIPTION

Dog is a program similar to cat (1), but it has many more features.
Dog is able to translate the input.

## OPTIONS

Command-line options are based on cat.
Dog does the translation after a cat listened.

-c or --convert

* do (asymmetric) conversion such as rot13

-e or --encode

* do symmetric encoding such as base64

-d or --decode

* do symmetric decoding such as base64

-h or --hash

* do checksum/hash calculation such as SHA-1

-i or --iconv

* decode then encode in input:output character encodings such as utf8:sjis

-l or --list

* show file type and inspect its contents (`tar -tvf` etc.)

## SEE ALSO

[cat](http://linux.die.net/man/1/cat)(1)
