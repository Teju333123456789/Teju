<script>
// A function to check if n is palindrome
function isPalindrome(n)
{
	// Find reverse of n
	var rev = 0;
	for (var i = n; Math.trunc(i) > 0; i /= 10)
	{
		rev = ((rev*10) + (Math.trunc(i)%10));
		
		}

	// If n and rev are same, then n is palindrome
	return (n==rev);
}
