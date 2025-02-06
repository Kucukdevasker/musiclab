import time
from pynput.keyboard import Controller

keyboard = Controller()

def press_key(key):
    keyboard.press(key)
    keyboard.release(key)
    print(f"Pressed '{key}'")

def press_keys_simultaneously(keys):
    for key in keys:
        keyboard.press(key)
    for key in keys:
        keyboard.release(key)
    print(f"Pressed keys simultaneously: {', '.join(keys)}")

def press_and_hold_keys(keys, hold_time):
    for key in keys:
        keyboard.press(key) 
    time.sleep(hold_time)  
    for key in keys:
        keyboard.release(key)  

sequence1 = [
    ('y', 78), ('o', 78), ('ş', 78), ('x', 0),
    ('y', 78), ('z', 0), ('o', 78), ('ş', 78),
    ('x', 0), ('y', 78), ('o', 78), ('z', 0),
    ('ş', 78), ('x', 0), ('y', 78), ('o', 78),
    ('ş', 78), ('y', 78), ('o', 78), ('ş', 78),
    ('x', 0), ('y', 78), ('z', 0), ('o', 78),
    ('ş', 78), ('x', 0), ('y', 78), ('o', 78),
    ('z', 0), ('ş', 78), ('x', 0), ('y', 78),
    ('o', 78), ('ş', 78), ('y', 78), ('o', 78), 
    ('ş', 78)
]

sequence1_2 = [
    ('y', 78), ('o', 78), ('ş', 78), ('x', 0),
    ('y', 78), ('z', 0), ('o', 78), ('ş', 78),
    ('x', 0), ('y', 78), ('o', 78), ('z', 0),
    ('ş', 78), ('x', 0), ('y', 78), ('o', 78),
    ('ş', 78), ('y', 78), ('o', 78), ('ş', 78),
    ('x', 0), ('y', 78), ('z', 0), ('o', 78),
    ('ş', 78), ('x', 0), ('y', 78), ('o', 78),
    ('z', 0), ('ş', 78), ('x', 0), ('y', 78),
    ('o', 78), ('ş', 78), ('ş', 78), ('x', 0),
    ('y', 78), ('o', 78)
]

sequence2 = [
    ('z', 0), ('z', 0),
    ('y', 78), ('k', 78), ('p', 78), ('x', 0),
    ('y', 78), ('z', 0), ('k', 78), ('p', 78),
    ('x', 0), ('y', 78), ('k', 78), ('z', 0),
    ('p', 78), ('x', 0), ('y', 78), ('k', 78),
    ('p', 78), ('y', 78), ('k', 78), ('p', 78),
    ('x', 0), ('y', 78), ('z', 0), ('k', 78),
    ('p', 78), ('x', 0), ('y', 78), ('k', 78),
    ('z', 0), ('p', 78), ('x', 0), ('y', 78),
    ('k', 78), ('p', 78), ('y', 78), ('k', 78), 
    ('p', 78)
]

sequence3 = [
    ('z', 0),
    ('w', 78), ('f', 78), ('y', 78), ('x', 0),
    ('w', 78), ('z', 0), ('f', 78), ('y', 78),
    ('x', 0), ('w', 78), ('f', 78), ('z', 0),
    ('y', 78), ('x', 0), ('w', 78), ('f', 78),
    ('y', 78), ('w', 78), ('f', 78), ('y', 78),
    ('x', 0), ('w', 78), ('z', 0), ('f', 78),
    ('y', 78), ('x', 0), ('w', 78), ('f', 78),
    ('z', 0), ('y', 78), ('x', 0), ('w', 78),
    ('f', 78), ('y', 78), ('w', 78), ('f', 78),
    ('y', 78)
]

sequence4 = [
    ('z', 0), ('z', 0),
    ('w', 78), ('t', 78), ('h', 78), ('o', 78), ('x', 0),
    ('w', 78), ('t', 78), ('h', 78), ('o', 78), ('x', 0),
    ('w', 78), ('t', 78), ('h', 78)
]

sequence5 = [
    ('z', 0), ('z', 0),
    ('w', 78), ('d', 78), ('g', 78), ('o', 78), ('x', 0),
    ('w', 78), ('d', 78), ('g', 78), ('o', 78), ('x', 0),
    ('w', 78), ('d', 78), ('g', 78)
]

sequence7 = [
    ('d', 78), ('g', 78), ('o', 78), ('ş', 78),
    ('g', 78), ('o', 78), ('ş', 78), ('x', 0),
    ('g', 78), ('w', 78), ('d', 78), ('g', 78),
    ('o', 78), ('d', 78), ('g', 78), ('o', 78),
    ('ş', 78), ('g', 78), ('o', 78), ('ş', 78),
    ('x', 0), ('g', 78), ('w', 78), ('d', 78),
    ('g', 78), ('o', 78), ('d', 78), ('g', 78),
    ('o', 78)
]

sequence8 = [
    ('e', 78), ('u', 78), ('o', 78), ('p', 78),
    ('u', 78), ('x', 0), ('w', 78), ('e', 78),
    ('u', 78), ('w', 78), ('e', 78), ('u', 78),
    ('o', 78), ('e', 78), ('u', 78), ('o', 78),
    ('p', 78), ('u', 78), ('x', 0), ('w', 78),
    ('e', 78), ('u', 78), ('w', 78), ('e', 78),
    ('u', 78), ('o', 78), ('u', 78), ('e', 78),
    ('w', 78), ('u', 78), ('e', 78), ('w', 78),
    ('z', 0), ('u', 78)
]

sequence9 = [
    ('d', 78), ('t', 78), ('y', 78), ('h', 78),
    ('j', 78), ('o', 78), ('j', 78), ('h', 78)
]

sequence10 = [
    ('d', 78), ('t', 78), ('y', 78), ('h', 78),
    ('j', 78), ('o', 78), ('l', 78), ('ş', 63),('p', 63),
    ('ş', 63), ('p', 63), ('ş', 63), ('o', 78),
    ('j', 78), ('h', 78)
]

sequence11 = [
    ('d', 78), ('t', 78), ('y', 78), ('h', 78),
    ('j', 78), ('o', 78), ('l', 78), ('ş', 78),
    ('x', 0),('t', 78), ('y', 78), ('h', 78),
    ('j', 78), ('o', 78), ('l', 78),('p', 78),
]
def dumdim():
    press_keys_simultaneously(['w', 'd', 'g', 'o'])
    time.sleep(0.1)  
    press_keys_simultaneously(['w', 'd', 'g', 'o'])
    time.sleep(0.13)  
    press_keys_simultaneously(['a', 'y', 'k'])
    time.sleep(0.13)  

    press_keys_simultaneously(['a', 'y'])
    time.sleep(0.140)  
    press_keys_simultaneously(['a', 'y'])
    time.sleep(0.140)  
    press_keys_simultaneously(['w', 'u'])
    time.sleep(0.140)  
    press_keys_simultaneously(['e', 'k'])
    time.sleep(0.140)  
    press_keys_simultaneously(['d', 'o'])
    time.sleep(0.140)  
    press_keys_simultaneously(['t', 'p'])
    time.sleep(0.140)  
    press_keys_simultaneously(['d', 'o'])
    time.sleep(0.140)  
    press_keys_simultaneously(['t', 'p'])
    time.sleep(0.140)  
    press_keys_simultaneously(['d', 'o'])
    time.sleep(0.140)  
    press_keys_simultaneously(['h', 'x', 't'])
    time.sleep(0.140)  
    press_keys_simultaneously(['z','y', 'ş'])
    time.sleep(0.140)  
    press_keys_simultaneously(['t', 'p'])
    time.sleep(0.140)  
    press_keys_simultaneously(['d', 'o'])
    time.sleep(0.140)  
    press_keys_simultaneously(['e', 'k'])
    time.sleep(0.140)  
    press_keys_simultaneously(['w', 'h'])
    time.sleep(0.140)  
    press_keys_simultaneously(['a', 'y'])
    time.sleep(0.140)  
    
    press_keys_simultaneously(['a', 'y'])
    time.sleep(0.140)  
    press_keys_simultaneously(['a', 'y'])
    time.sleep(0.140)  
    press_keys_simultaneously(['w', 'u'])
    time.sleep(0.140)  
    press_keys_simultaneously(['e', 'k'])
    time.sleep(0.140)  
    press_keys_simultaneously(['d', 'o'])
    time.sleep(0.140)  
    press_keys_simultaneously(['t', 'p'])
    time.sleep(0.140)  
    press_keys_simultaneously(['d', 'o'])
    time.sleep(0.140)  
    press_keys_simultaneously(['t', 'p'])
    time.sleep(0.140)  
    press_keys_simultaneously(['d', 'o'])
    time.sleep(0.140)  
    press_keys_simultaneously(['h', 'x', 't'])
    time.sleep(0.140)  
    press_keys_simultaneously(['z','y', 'ş'])
    time.sleep(0.140)  
    press_keys_simultaneously(['t', 'p'])
    time.sleep(0.140)  
    press_keys_simultaneously(['d', 'o'])
    time.sleep(0.140)  
    press_keys_simultaneously(['e', 'k'])
    time.sleep(0.140)  
    press_keys_simultaneously(['w', 'h', 'z', 'z'])
    time.sleep(0.140)  

    press_keys_simultaneously(['y', 'k', 'x', 'y', 'z'])
    time.sleep(0.140)  
    press_keys_simultaneously(['y', 'o', 'x', 'h', 'z'])
    time.sleep(0.140)  
    press_keys_simultaneously(['y', 'k', 'x', 'y', 'z'])
    time.sleep(0.140)  
    press_keys_simultaneously(['y', 'o', 'x', 'h', 'z'])
    time.sleep(0.140)  
    press_keys_simultaneously(['y', 'k', 'x', 'y', 'z'])
    time.sleep(0.140)  
    press_keys_simultaneously(['y', 'o', 'x', 'h', 'z'])
    time.sleep(0.140)  
    press_keys_simultaneously(['y', 'k', 'x', 'y', 'z'])
    time.sleep(0.140)  
    press_keys_simultaneously(['y', 'o', 'x', 'h', 'z'])
    time.sleep(0.140)  
    press_keys_simultaneously(['y', 'k', 'x', 'y', 'z'])
    time.sleep(0.27)  

def humhim():
    keyboard.press('j')  
    time.sleep(0.45)  
    keyboard.release('j')
    keyboard.press('p')  
    time.sleep(0.65)  
    keyboard.release('p')
    keyboard.press('j')  
    time.sleep(0.35)  
    keyboard.release('j')

    press_key('y')
    time.sleep(0.06)
    press_key('g')
    time.sleep(0.06)
    press_key('y')
    time.sleep(0.06)
    press_key('p')
    time.sleep(0.06)
    keyboard.press('y')  
    time.sleep(0.4)  
    keyboard.release('y')
    keyboard.press('g')  
    time.sleep(0.6)  
    keyboard.release('g')
    time.sleep(0.1)

    keyboard.press('g')  
    time.sleep(0.12)  
    keyboard.release('g')
    keyboard.press('p')  
    time.sleep(0.35)  
    keyboard.release('p')
    keyboard.press('g')  
    time.sleep(0.15)  
    keyboard.release('g')

    keyboard.press('u')  
    time.sleep(0.4)  
    keyboard.release('u')
    keyboard.press('y')  
    time.sleep(0.6)  
    keyboard.release('y')
    time.sleep(0.1)

    keyboard.press('y')  
    time.sleep(0.12)  
    keyboard.release('y')
    keyboard.press('p')  
    time.sleep(0.35)  
    keyboard.release('p')
    keyboard.press('y')  
    time.sleep(0.15)  
    keyboard.release('y')

    keyboard.press('j')  
    time.sleep(0.4)  
    keyboard.release('j')
    keyboard.press('u')  
    time.sleep(0.6)  
    keyboard.release('u')
    time.sleep(0.1)

    keyboard.press('u')  
    time.sleep(0.12)  
    keyboard.release('u')
    keyboard.press('p')  
    time.sleep(0.35)  
    keyboard.release('p')
    keyboard.press('u')  
    time.sleep(0.15)  
    keyboard.release('u')

def dubdib():
    keyboard.press('j')  
    time.sleep(0.18)  
    keyboard.release('j')
    press_key('x')
    time.sleep(0)

    for k in range(3):
        press_and_hold_keys(['e', 'p'], 0.4)
    
    press_key('j')  
    time.sleep(0.0)  
    press_key('z')
    time.sleep(0)
    press_key('j')  
    time.sleep(0.2)  
    
    press_key('y')  
    time.sleep(0.0)  
    press_key('x')
    time.sleep(0.0)  
    press_key('y')  
    time.sleep(0.16)  
    press_key('y')  
    time.sleep(0.0)  
    press_key('z')
    time.sleep(0)
    press_key('y')  
    time.sleep(0.2)  
    press_key('x')
    time.sleep(0)

    for k in range(3):
        press_and_hold_keys(['g'], 0.4)
    press_key('z')
    time.sleep(0)




time.sleep(5)

for z in range(1):
    #Execute the first sequence
    for key, pause_ms in sequence1:
        press_key(key)
        time.sleep(pause_ms / 1000.0)  




    press_keys_simultaneously(['y', 'o', 'ş'])
    press_key('x')
    time.sleep(0)
    press_key('y')
    time.sleep(0)
    press_key('z')
    time.sleep(0)
    time.sleep(0.15)  
    press_keys_simultaneously(['y', 'o', 'ş'])
    press_key('x')
    time.sleep(0)
    press_key('y')
    time.sleep(0)
    press_key('z')
    time.sleep(0)
    time.sleep(0.21)  

    for key, pause_ms in sequence2:
        press_key(key)
        time.sleep(pause_ms / 1000.0)  


    press_keys_simultaneously(['y', 'k', 'p'])
    press_key('x')
    time.sleep(0)
    press_key('y')
    time.sleep(0)
    press_key('z')
    time.sleep(0)
    time.sleep(0.15)  
    press_keys_simultaneously(['y', 'k', 'p'])
    press_key('x')
    time.sleep(0)
    press_key('y')
    time.sleep(0)
    press_key('z')
    time.sleep(0)
    time.sleep(0.21)  


    for key, pause_ms in sequence3:
        press_key(key)
        time.sleep(pause_ms / 1000.0)  
    press_keys_simultaneously(['w', 'f', 'y', 'o'])
    time.sleep(0.15)  
    press_keys_simultaneously(['w', 'f', 'y', 'o'])
    time.sleep(0.21)  

    for key, pause_ms in sequence4:
        press_key(key)
        time.sleep(pause_ms / 1000.0)  
    press_keys_simultaneously(['w', 't', 'o', 'h'])
    time.sleep(0.15)  
    press_keys_simultaneously(['w', 't', 'o', 'h'])
    time.sleep(0.21)  

    
    for key, pause_ms in sequence5:
        press_key(key)
        time.sleep(pause_ms / 1000.0)  
    dumdim()

    
    for _ in range(2):
        press_key('z')
        time.sleep(0.0)  

    keyboard.press('y')  
    time.sleep(1.2)  
    keyboard.release('y')

    press_key('y')
    time.sleep(0.50)

for key, pause_ms in sequence1_2:
    press_key(key)
    time.sleep(pause_ms / 1000.0)  
press_keys_simultaneously(['d', 'ş'])
time.sleep(0.15)  
press_keys_simultaneously(['d', 'ş'])
time.sleep(0.21)  
for _ in range(2):
    press_key('z')
    time.sleep(0.0)  

for key, pause_ms in sequence7:
    press_key(key)
    time.sleep(pause_ms / 1000.0)  
press_keys_simultaneously(['d', 'ş'])
time.sleep(0.15)  
press_keys_simultaneously(['d', 'ş'])
time.sleep(0.21)  
for _ in range(2):
        press_key('z')
        time.sleep(0.0)  

for key, pause_ms in sequence8:
    press_key(key)
    time.sleep(pause_ms / 1000.0)  

humhim()
dubdib()



press_and_hold_keys(['w', 'h', 'o', 'ş'], 0.7)
press_key('x')
time.sleep(0.0)  

for _ in range(3):
    for key, pause_ms in sequence9:
        press_key(key)
        time.sleep(pause_ms / 1000.0)  

for key, pause_ms in sequence10:
    press_key(key)
    time.sleep(pause_ms / 1000.0)  

keyboard.press('y')  
time.sleep(0.5)  
keyboard.release('y')

for _ in range(5):
    press_key('j')
    time.sleep(0.04)
    press_key('u')
    time.sleep(0.04)

press_key('y')
time.sleep(0.078)

press_key('u')
time.sleep(0.078)

press_key('z')
time.sleep(0.0)

press_keys_simultaneously(['d', 'y', 'j', 'z'])
time.sleep(0.6)





press_and_hold_keys(['w', 'h', 'o', 'ş'], 0.7)

press_key('x')
time.sleep(0.0)


for _ in range(5):
    for key, pause_ms in sequence9:
        press_key(key)
        time.sleep(pause_ms / 1000.0)  

for key, pause_ms in sequence11:
        press_key(key)
        time.sleep(pause_ms / 1000.0)

press_and_hold_keys(['d', 'ş'], 0.7)
keyboard.press('y')  
time.sleep(0.7)  
keyboard.release('y')
keyboard.press('j')  
time.sleep(0.7)  
keyboard.release('j')
keyboard.press('g')  
time.sleep(0.7)  
keyboard.release('g')
