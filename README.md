# test

long string2int(char *s){
    long i;
    i = 0;
    while(*s >= '0' && *s <= '9')
    {
        i = i * 10 + (*s - '0');
        s++;
    }
    if (*s == '\0') {
        return i;
    } else {
        return -1;
    }
}
