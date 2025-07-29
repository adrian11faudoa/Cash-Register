Subject:

Find a value in an Array:
```
    const targetArr = cid.find(([denominationName]) => denominationName === changeDenomination);
```

Loop through values in an Array:
```
    cid.map(([denominationName, amount]) => `<p>${currencyNameMap[denominationName]}: $${amount}</p>`)
```

Check for a keyboard interaction in an Input:
```
    cash.addEventListener('keydown', e => {
    if (e.key === 'Enter') {
        checkResults();
    }
    });
```

