# morse = {
    'A': '*-', 'B': '-***',
    'C': '-*-*', 'D': '-**',
    'E': '*', 'F': '**-*',
    'G': '--*', 'H': '****',
    'I': '**', 'A': '*---',
    'K': '-*-','L': '*-**',
    'M': '--', 'N': '-*',
    'O': '---','P': '*--*',
    'Q': '--*-', 'R': '*-*',
    'S': '***', 'T': '-',
    'U': '**-', 'V': '***-',
    'W': '*--', 'X': '-*--',
    'Y': '-*--', 'Z': '--**',   
}
myStr = input().split()
newStr = ''
for item in myStr:
    for letter in item:
        if letter in morse:
            newStr += morse[letter]
    print(newStr)
    newStr = ''
