```uml
@startuml
start
if(weather == 0)
:快晴です;
else if(weather == 1)
:曇りです;
else if(weather == 2)
:雨です;
else
:不明です;
endif
end
@enduml
```
