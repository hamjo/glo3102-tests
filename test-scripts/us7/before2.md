## url
POST {{url}}/bills/{{bill-id}}

## tests
pm.test('Status code is 200', function(){
    pm.response.to.have.status(200);
});