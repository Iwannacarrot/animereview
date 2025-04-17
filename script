function addReview() {
  const title = document.getElementById('title').value;
  const comment = document.getElementById('comment').value;
  const rating = document.getElementById('rating').value;

  const reviewDiv = document.createElement('div');
  reviewDiv.className = 'review';
  reviewDiv.innerHTML = `
    <h3>${title} ⭐ ${rating}/10</h3>
    <p>${comment}</p>
  `;

  document.getElementById('reviews').appendChild(reviewDiv);

  // 입력값 초기화
  document.getElementById('title').value = '';
  document.getElementById('comment').value = '';
  document.getElementById('rating').value = '';
}
