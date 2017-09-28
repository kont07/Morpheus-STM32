# Morpheus-STM32
A cheap 3D printer controller board for use with a "Blue Pill" STM32F1 generic board. Based on http://reprap.org/wiki/SinapTec
(work in progress)

It's design goals are:
  Follow the KISS Principle https://en.wikipedia.org/wiki/KISS_principle
  Low cost
  Single sided copper board
  DIY-able (easy to make via toner transfer)
  Only through-hole components
  Only the very basic a printer needs
  Keep bed circuit separated/optional (if you are making a PLA only printer, you don't need to populate the bed circuit zone)

Features:
  4 (X, Y, Z, E0) Pololu-like steppers
  3 mosfets (E0 heater, fan and bed heater)
  3 (X, Y, Z) MIN endstops
  2 thermistors (E0 and bed)
