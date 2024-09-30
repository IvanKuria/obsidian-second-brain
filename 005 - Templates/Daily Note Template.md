<< [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').subtract(1, 'days').format('YYYY-MM-DD') %>|Yesterday]] | [[<% moment(tp.file.title, 'YYYY-MM-DD').add(1, 'days').format('YYYY-MM-DD') %>|Tomorrow]] >>

> [!multi-column]
> 
>> [!todo] Task Due Today
>> ```tasks
>> not done
>> due today
>> hide due date
>> ```
> 
>> [!danger] Overdue Tasks
>> ```tasks
>> not done
>> due today
>> hide due date
>> ```
> 
>> [!success] Completed Tasks
>> ```tasks
>> done today
>> ```


## Tasks Due Today
```tasks
not done
due today
hide due date
```

## Overdue Tasks
```tasks
not done
due before today
hide due date
```

## Completed Tasks
```tasks
done today
```