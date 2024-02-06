# QR-code-generator
# This is my first Git-Repository
# Author - Rishav Guha.

# main project
import qrcode
myqr = qrcode.make("https://www.amazon.com/")
myqr.save("myqr.png")
