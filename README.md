        function updateValue(e) {
            log.textContent = e.target.value;
        }


        Ou

        function updateValue(e) {

            if((e.target.value).includes("onerror")) {
                log.innerHTML = "ahahha nice try !"
            } else {

                log.innerHTML = e.target.value;
            }
            
        }
