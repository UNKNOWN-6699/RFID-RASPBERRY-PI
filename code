import serial 
def
read_rfid():
ser=serial.Serial("/dev/ttyUSB0")
ser.baudrate=9000
data=ser.read(15)
ser.close()
return data
try:
while True:
id = read_rfid() 
print(id)
if id==(b'270017A0BF2F270): 
print("Access Granted")
else:
print("Access deneid") 
finally: 
print("Hello")
