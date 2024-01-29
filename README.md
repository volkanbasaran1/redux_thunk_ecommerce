![ekran](https://github.com/volkanbasaran1/redux_thunk_ecommerce/assets/76842256/5c671376-66e8-48c0-9250-242c79a850d4)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>E-Ticaret Uygulaması</h1>
  <p>Bu proje, Redux Thunk kullanılarak geliştirilmiş bir e-ticaret uygulamasını içerir.</p>
  <h2>Proje Açıklaması</h2>
  <p>Bu e-ticaret uygulaması, kullanıcıların ürünleri listeleyebileceği, sepete ekleyebileceği ve sipariş verebileceği basit bir platform sunar. Redux Thunk, asenkron işlemleri yönetmek ve API çağrıları yapmak için kullanılmıştır.</p>
  <h2>Başlangıç</h2>
  <ol>
    <li>
      <strong>Projeyi Klonlayın</strong>
      <pre><code>git clone https://github.com/your-username/e-commerce-app.git
cd e-commerce-app</code></pre>
    </li>
    <li>
      <strong>Gerekli Paketleri Yükleyin</strong>
      <pre><code>npm install</code></pre>
    </li>
    <li>
      <strong>Uygulamayı Başlatın</strong>
      <pre><code>npm start</code></pre>
      Uygulama, varsayılan olarak <code>http://localhost:3000</code> adresinde çalışacaktır. Tarayıcınızı açın ve uygulamayı görmelisiniz.
    </li>
  </ol>
  <h2>Kullanılan Teknolojiler</h2>
  <ul>
    <li>React</li>
    <li>Redux ve Redux Thunk</li>
    <li>CSS Modules</li>
  </ul>
  <h2>Özellikler</h2>
  <ol>
    <li>Ürünleri listeleme</li>
    <li>Sepete ürün ekleme ve çıkarma</li>
    <li>Sipariş verme</li>
  </ol>
  <h2>Redux Thunk Kullanımı</h2>
  <p>Redux Thunk, bu uygulama içinde asenkron işlemleri yönetmek ve API çağrıları yapmak için kullanılmıştır. Thunk middleware, özellikle sepete ürün ekleme ve sipariş verme gibi asenkron işlemleri ele alır.</p>
  <pre><code>
// Örnek bir Redux Thunk eylemi
export const addToCart = (product) => {
  return (dispatch, getState) => {
    // Asenkron işlemler burada gerçekleşir
    dispatch({ type: 'ADD_TO_CART', payload: product });
  };
};
  </code></pre>
  <h2>Katkıda Bulunma</h2>
  <ol>
    <li>Bu depoyu çatallayın (fork) ve yerel makinenize klonlayın.</li>
    <li>Değişikliklerinizi yapın ve pull request oluşturun.</li>
  </ol>
</body>
</html>
