function insertAtCursor(){
    (async () => {

        let input = document.querySelector('textarea.FormControl');
        
        let pos = input.selectionStart
        let front = (input.value).substring(0, pos);  
        let back = (input.value).substring(pos, input.value.length); 
        
        input.value = front+'[beth][/beth]'+back;
        pos = pos + 6;
        
        input.selectionStart = pos;
          input.selectionEnd = pos;
          input.focus();
      
        })()
}
