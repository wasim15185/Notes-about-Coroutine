# Notes about Corotines

### Basic Terms of Corotines

- Job
- Scope for Corotines
- Dispatcher
- async/await


## What is coroutines ?
- Coroutines is a non blocking asynchronous <b>Light Weight-Thread</b> . 

## What is Callback Hell ?
         
```
fun doWork1(success:()->Unit  ){ }

fun doWork2(success:()->Unit   ){ }

fun doWork3(success:()->Unit   ){ }

fun doWork4(success:()->Unit   ){ }


fun main() {

    doWork1 {                   
        doWork2 {
            doWork3 {
                doWork4 {
                              // <--- It is callback hell
                }
            }
        }
    }


}

```
         


## Why we should use coroutines ?
- It is Light-Weight than Thread.
- It removes the <b>Callback Hell</b> from code.<br/> 
- It is asynchronous in nature
  
     

