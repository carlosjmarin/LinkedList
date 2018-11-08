public void add(T element)
{
  LinearNode<T> node = new LinearNode<T>(element)
 
  Comparable<T> comparableElement = (Comparable<T>element;
 
  LinearNode<T> current = head;
  LinearNode<T> previous = null;
  
  boolean found = false;
  
  while (current != null && !found)
    if(comparableElement.compareTo(current.getElement()) <= 0 )
      found = true;
    else
    {
      previous = current;
      current = current.getNext();
     }
     
     if (count == 0) //then list was empty
     {
        head = node;
        tail = node;
      }
       else if (previous == null) //I am inserting at the head
       {
          node.setNext(head);
          head = node;
        }
        else if (current == null) //then im inserting at the tail
        {
          tail.setNext(node);
          tail = node;
        }
        else //im inserting in the middle of the list
        {
         node.setNext(current);
         previous.setNext(node);
         }
         count++
         }
         
         public addToFront(T element)//for unordered listss
         {
            LinearNode<T> node = new LinearNode<T>(element);
            
            if (count = 0)
            {
              tail = node;
            }
            else
            {
              node.setNext(head);
             }
             
              head = node;
              
              count++;
         }
        public void addToRear(T element)
        {
         LinearNode<T> node = new LinearNode<T>(element);
            
            if (count = 0)
            {
              head = node;
            }
            else
            {
              tail.setNext(head);
             }
             
              tail = node;
              
              count++;
          }
        public addAfter(T element,T targetElement)
        {
            LinearNode<T> node = new LinearNode;
            boolean found = false;
            LinearNode<T> previous = null;
            LinearNOde<T> current = head;
            
            while (current != null && !found)
            {
            //did i find the target elemenet
              if( targetElement.equals(current.getElement()))
              {
              //check if next one is different
                if(current.getNext() == null)
                {//if next is null there is no next one candidate was right
                found = true;
                 }
                 else if(!targetElement.equals(current.getNext().getElement()))
                  {
                    found = true;
                  }
                  else
                  {
                     current = current.getNext();
                   }
               }
               else
                {
                  
                  current = current.getNext();
                 }
               if(!found)
                throw new ElementNotFOundException("LinkedList");
                
                if(current == tail
                {
                  //we are inserting after the tail
                  current.setNext(node);
                  tail = node;
                }
                else
                {
                  //we are isnerting in the middle
                  node.setNext(current.getNext());//has to go first
                  current.setNext(node);
                }
                count++;
            }   
            
        }
        
      }
