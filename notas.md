### Notas de [APRENDE LARAVEL 8 DESDE CERO EN MENOS DE 2 HRS](https://www.youtube.com/watch?v=a-4923Uyu54&t=843s&ab_channel=VidaMRR-Programacionweb)

Utilizaremos POO y Model View Controller.
Vamos a consumir datos a traves de modelos. 

#### Directivas
    @if (Route::has('register'))
                            <a href="{{ route('register') }}" class="ml-4 font-semibold text-gray-600 hover:text-gray-900 dark:text-gray-400 dark:hover:text-white focus:outline focus:outline-2 focus:rounded-sm focus:outline-red-500">Register</a>
                        @endif


#### Rutas
Se usa un paquete llamado route

    use Illuminate\Support\Facades\Route;

Aca se pueden agregar nuestras rutas para mostrar las vistas. 

    Route::get('/', function () {
        return view('welcome');
    });

#### Contenido
Laravel nos permite crear plantillas base y mostrar contenido que herede los estilos o componentes
de la plantilla master.

