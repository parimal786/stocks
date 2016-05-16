-> Use of m.startComputation() and m.endComputation() in

        feed.onChange(function(stock) {
            m.startComputation();
            stocks[stock.symbol] = stock;
            ctrl.stocks(stocks);
            ctrl.last(stock);
            m.endComputation();
        });

1.Clone this repository

2.Open a command prompt and navigate to the application directory

cd stock

3.Install the dependencies

npm install

4.Run the server

node server

5.Run the application. Open a browser and access the following URL:

http://localhost:3000        
