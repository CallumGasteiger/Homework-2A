def showTwoPictures():
  file = pickAFile()
  file2 = pickAFile()
  file = makePicture(file)
  file2 = makePicture(file2)
  show(file)
  show(file2)
def printInvite():
  print "Please come to my WILD PARTY BONANZA!"
  print "Saturday at 6 at 47 Maple Street"
def printDisclaimer():
  print "If the Habeas Corpus of Subpoena gives an Objection to the Judicial Jury Baliff"
  print "The host is not responsible for loss of property, limbs, or soul"
  print "The dinosaurs are probably harmless but if you get eaten it's not my fault"
  print "By accepting this invite you waive ownership of your life"
def printFullInvite():
  printInvite()
  printDisclaimer()
def main():
  showTwoPictures()
  printFullInvite()
main()
