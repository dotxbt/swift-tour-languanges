# Swift Tour Languages

## Comments
```swift
// line comment

/*
   multiline comment
*/
```

## Constants and Variables

```swift
let iniKonstanta = 10
var iniVariabel = 100

var emptyString = ""
var anotherEmptyString = String() 
var iniSingleLineString: String = "Ini String" + " Hore Kore" // concat
let iniMultiLineString = """
The White Rabbit put on his spectacles.  "Where shall I begin,
please your Majesty?" he asked.

"Begin at the beginning," the King said gravely, "and go on
till you come to the end; then stop."
"""
let countChar = iniMultiLineString.count

var iniInteger: Int = 2983
var iniUnsignedInteger: UInt = 2983
var iniDouble: Double = 72397480
var iniFloat: Float = 3.14
var iniChar: Character = "C"
var iniBoolean: Bool = true

// Numeric literals
var iniDecimal = 45
var iniDecimalExponent = 45.2374e1
var iniBinary = 0b10010110
var iniOctal = 0o21344
var iniHexadecimal = 0x131ffcc
var iniHexadecimalDouble = 0x13C.3p02

let paddedDouble = 000123.456
let oneMillion = 1_000_000
let justOverOneMillion = 1_000_000.000_000_1

// tipe bentukan
typealias BilBulPositvif32 = UInt32
var iniBilBulPos32: BilBulPositvif32 = 19827319

// contoh print var or let
print("cara print \(iniBoolean) dengan \(iniString) di dalam print")
```

## Convertion

```swift
// test nilai dan batas penampungan
let cannotBeNegative: UInt8 = -1 // error tidak bisa negatif
let tooBig: Int8 = Int8.max + 1 // error angka terlalu besar

// menjumlahkan 2 ukuran memori berbeda
let twoThousand: UInt16 = 2_000
let one: UInt8 = 1
let twoThousandAndOne = twoThousand + UInt16(one) // menjadi UInt16


// Konversi Nilai 
// pattern : <Type>(<value>)
let three = 3 // Int
let pointOneFourOneFiveNine = 0.14159 // Double
let pi = Double(three) + pointOneFourOneFiveNine // Double
let intPi = Int(pi) // Int

```
