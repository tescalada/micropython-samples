# micropython-samples
A place for assorted code ideas for MicroPython.

mutex: A class providing mutal exclusion enabling interrupt handlers and the main program to
access shared data in a manner which ensures data integrity.

watchdog: How to access the simpler of the Pyboard's watchdog timers.

ds3231_pb: Driver for the DS3231 low cost precison RTC, including a facility to calibrate the
Pyboard's RTC from the DS3231

radio: A trivial class simplifying the use of the nRF24L01 radio for the case where a wireless
link between two devices is required.

Buildcheck: Raise an exception if a firmware build is earlier than a given date.

Any code placed here is released under the MIT License (MIT).  
The MIT License (MIT)  
Copyright (c) 2015 Peter Hinch  
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.