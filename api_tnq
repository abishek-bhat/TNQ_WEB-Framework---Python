from django.shortcuts import render
from django.http import HttpResponse
def index(request):
    return render(request,'form.html')
def add(request):
    A=int(request.GET["A"])
    B=int(request.GET["B"])
    res=A+B
    res_sub=A-B
    res_mul=A*B
    res_div=A/B
    return render(request,'result.html',{"Result:res"},{"Result,:res_sub"},{"Result,:res_mul"},{"Result,:res_div"})