# Implement order

- Create models
    - Order
- Create DAO
    - OrderDao. To get the order for a specific user create method getByUser().
- Create service  
    - OrderService
        ```java
        public interface OrderService {
            Order completeOrder(ShoppingCart shoppingCart);
            
            List<Order> getOrdersHistory(User user);
        }
        ``` 
- In the `mate/academy/Main.main()` method create instance of OrderService using injector and test all methods from it.   

__Attention!!!__: you can have some problem with naming of the table. Let's use `orders` instead of `order`.

__You can check yourself using this__ [checklist](https://mate-academy.github.io/jv-program-common-mistakes/hibernate/add-order/add-order-hw)  

### Model structure 
![pic](Hibernate_Cinema_Uml.png)

# Выполнить заказ

- Создавать модели
    - Заказ
- Создать ДАО
    - ОрденДао. Чтобы получить заказ для конкретного пользователя, создайте метод getByUser().
- Создать сервис
    - Служба заказов
        ```java
        общедоступный интерфейс OrderService {
            Order CompleteOrder(Корзина покупокКорзина покупок);
            
            List<Order> getOrdersHistory (Пользователь-пользователь);
        }
        ```
- В методе `mate/academy/Main.main()` создайте экземпляр OrderService с помощью инжектора и протестируйте все его методы.

__Внимание!!!__: могут возникнуть проблемы с именованием таблицы. Давайте использовать «заказы» вместо «заказ».

__Вы можете проверить себя, используя этот__ [контрольный список](https://mate-academy.github.io/jv-program-common-mistakes/hibernate/add-order/add-order-hw)

### Структура модели
![pic](Hibernate_Cinema_Uml.png)