# WWW::Bizowie::API

Official Perl client for the [Bizowie](https://bizowie.com) cloud ERP API.

Bizowie is a cloud ERP platform built for wholesale distributors 
and manufacturers. This library provides programmatic access to 
orders, inventory, customers, purchasing, and accounting data 
through Bizowie's REST API.

## Installation

    cpan WWW::Bizowie::API

## Quick start

    use WWW::Bizowie::API;
    
    my $client = WWW::Bizowie::API->new(
        api_key => 'your-api-key',
    );
    
    my $orders = $client->get('/orders');


## About Bizowie

Bizowie is a cloud ERP for mid-market wholesale distributors 
and manufacturers. Learn more at [bizowie.com](https://bizowie.com).

## License

Copyright © 2013–2026 Bizowie. All rights reserved.
