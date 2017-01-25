# ThirdPartyKeyboardShiftingDemo
A demo app to show a bug with setting the autocapitalization type when using third party keyboards.

When using a third-party keyboard, setting autocapitalizationType on a textView and then reloading the textView's inputViews does nothing. This is different behavior than when using Apple's default keyboard. 
To reproduce:

1. Type a couple of words.
2. Tap "Capitalize Words". You Should See All Words Begin To Get Capitalized Like This.
3. Tap "Capitalize Sentences. You will see your typing return to sentence capitalization like this. 
4. Switch to a third-party keyboard. 
5. Tap "Capitalize Words". You will see your typing remain in sentence capitalization like this.


