double x=0, y=0;
cin >> x >› y;
double d=(x*x - 4*y);
double a=0, b=0;
if (d >= 0) {
a= (x- sqrt(d))/2;
b= (x + sqrt(d))/2;
}
if (x= a+b) {
if (y= a*b) {
cout « a «<" +" « b«"=" « x « endl;
cout « a «"*" « b«"=" « y « endl;
cout « "Solving complete"s << endl;
