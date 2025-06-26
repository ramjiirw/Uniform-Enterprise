//CoreComms 1 - Cases Valid Last X Days


//DaysToTarget [Calculated Fields Tab - Core Code - Type: INT)
DateTime targetDate = data.TARGED;

if (data.AGREEDD != null && data.AGREEDD > DateTime.MinValue)
    targetDate = data.AGREEDD;
else if (data.EXTEND != null && data.EXTEND > DateTime.MinValue)
    targetDate = data.EXTEND;

int iDaysToTarget = data.CalculateCalendarDaysBetween(data.TodayD, targetDate);
string sDaysToTarget = iDaysToTarget.ToString();
return iDaysToTarget;


