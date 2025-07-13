let button=document.getElementById("button");
button.addEventListener("click",send);
let input=document.getElementById("information").value;
let array_lists=[];
let p=document.getElementById("p");
p.style.display="none"

function send(e) {
    e.preventDefault();
    let div=document.createElement("div");
    form.after(div);
    let input=document.getElementById("information").value;
    div.style.width="100%"
    p.style.display="block"
    array_lists.unshift(input);
    x=1
    while (x<array_lists.length) {
        let list_items=`<section id="list">
                    <h3>${x}: ${input}</h3>       
                    <button class="btn btn-outline-danger" id="exit">exit</button>
                </section> `;

        div.innerHTML=list_items;
        x++
        let exit=document.getElementById("exit");
        exit.addEventListener("click",remove);
        function remove() {
            let list=document.getElementById("list");
            div.remove(list);
        } 
    }
    
    
}





    